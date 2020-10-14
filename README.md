# Typescript Boilerplate

Set up ESLint and Prettier in every Typescript project hurts 😔

## Workspace

### Extensions

- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

### Settings

```json
$ cat .vscode/settings.json

{
  "editor.codeActionsOnSave": {
    "source.fixAll": true
  },
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.detectIndentation": false,
  "editor.formatOnSave": true,
  "editor.minimap.enabled": false,
  "editor.rulers": [80, 120],
  "editor.tabSize": 2,
  "eslint.validate": ["typescript"],
  "files.insertFinalNewline": true
}
```

## License

This project is distributed under the [MIT license](LICENSE)
