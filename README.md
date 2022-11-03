https://typescriptbook.jp/tutorials

```bash
## Install Node.js
nodenv local 16.13.1
echo 'export PATH="/usr/local/opt/node@16/bin:$PATH"' >> ~/.zshrc
source ~/.zshrc
node -v # v16.13.1

## Install TypeScript
npm install -g typescript
tsc -v # Version 4.5.5
```
