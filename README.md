# ✨Visual Studio Code for web-dev

A selection of the best extensions and configs for web development

## Navigation

- [Сode style and formatting](#-code-style-and-formatting)
- [Languages and snippets](#-languages-and-snippets)
- [Tools](#%EF%B8%8F-tools)
- [Interface](#interface)
- [Design](#-design)

## 💅 Code style and formatting

#### Code formatter using prettier ([prettier](https://prettier.io/))

`esbenp.prettier-vscode`

#### Format JavaScript and Typescript code using prettier-eslint package

`rvest.vs-code-prettier-eslint`

```json
{
  "editor.formatOnSave": true,
  "editor.formatOnPaste": false,
  "eslint.run": "onSave",
  "editor.codeActionsOnSave": {
    "source.fixAll": "always"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[jsx]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  }
}
```

#### Close and rename HTML tags

```
formulahendry.auto-close-tag
formulahendry.auto-rename-tag
```

#### Autoprefixer (Parse CSS and add vendor prefixes automatically)

`mrmlnc.vscode-autoprefixer`

#### Сoding styles for multiple developers ([Editorconfig](https://editorconfig.org/ "editorconfig.org"))

helps maintain consistent coding styles for multiple developers working on the same project across various editors and IDEs

`EditorConfig.EditorConfig`

#### JSON Formatter

`ClemensPeters.format-json`

## 🪄 Languages and snippets

#### CSS Intellisense for HTML

`ecmel.vscode-html-css`

#### Code snippets for JavaScript in ES6 syntax

`xabikos.JavaScriptSnippets`

#### Extensions for React, Redux in JS with babel and ES7 syntax

`skyran.js-jsx-snippets`

#### Plugin that autocompletes npm modules in import statements

`christian-kohler.npm-intellisense`

#### jQuery Code Snippets

`donjayamanne.jquerysnippets`

#### Language support for MDX

`unifiedjs.vscode-mdx`

#### Plugin that autocompletes filenames

`christian-kohler.path-intellisense`

#### Indented Sass syntax Highlighting, Autocomplete & Formatter ([SASS](https://sass-lang.com/))

`syler.sass-indented`

#### XML Language Support

`redhat.vscode-xml`

## ⚒️ Tools

#### JavaScript and TypeScript playground in your editor ([Quokka](https://quokkajs.com/))

`WallabyJs.quokka-vscode`

#### Manage npm dependencies from sidebar (npm, yarn, pnpm, bun)

`idered.npm`

#### Launch a development local Server with live reload feature for static & dynamic pages

`ritwickdey.LiveServer`

#### Real-time collaborative development

`ms-vsliveshare.vsliveshare`

#### Open any folder on a remote machine using SSH

```
ms-vscode-remote.remote-ssh
ms-vscode-remote.remote-ssh-edit
ms-vscode.remote-explorer
```

## 📁Interface

#### View a Git Graph of your repository

`mhutchie.git-graph`

#### Explorer Exclude (Hides service files, such as /node_modules)

`PeterSchmalfeldt.explorer-exclude`

```json
  "files.exclude": {
    "node_modules": true,
    "out": true
  },
  "toggleexcludedfiles.statusBar.enabled": true,
```

#### SQLite Viewer

`qwtel.sqlite-viewer`

#### View and run NPM scripts in the sidebar

`traBpUkciP.vscode-npm-scripts`

#### View word,excel files and using WYSIWYG editor for markdown

`cweijan.vscode-office`

#### Display pdf file

`tomoki1207.pdf`

#### Json for VSC

`ZainChen.json`

## 💖 Design

#### Theme (From Legendary Atom editor)

`NAPTheDevHcj.atom-background-modified`

#### Icons

```
PKief.material-icon-theme
Equinusocio.moxer-icons
```

#### Fonts

```
Consolas
Fira Code
```

#### Better comments (color and prefixes)

`aaron-bond.better-comments`

#### Styled-jsx syntax highlight and code intellisense

`blanu.vscode-styled-jsx`
