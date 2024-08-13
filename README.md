# my_conf

{
  "editor.fontFamily": "Operator Mono, Menlo, Monaco, 'Courier New', monospace",
  "editor.fontSize": 17,
  "editor.lineHeight": 25,
  "editor.letterSpacing": 0.5,
  "files.trimTrailingWhitespace": true,
  "editor.fontWeight": "400",
  "prettier.eslintIntegration": true,
  "editor.cursorStyle": "line",
  "editor.cursorWidth": 5,
  "editor.cursorBlinking": "solid",
  "editor.renderWhitespace": "all",
  "editor.formatOnSave": false,
  "editor.formatOnPaste": false,
  "editor.linkedEditing": true,
  "editor.occurrencesHighlight": "singleFile",
  "editor.suggest.insertMode": "replace",
  "editor.acceptSuggestionOnCommitCharacter": false,
  "files.defaultLanguage": "markdown",
  "explorer.autoReveal": false,
  "explorer.confirmDragAndDrop": false,
  "explorer.confirmDelete": false,
  "workbench.tree.indent": 15,
  "workbench.tree.renderIndentGuides": "always",
  "emmet.triggerExpansionOnTab": true,
  "git.confirmSync": false,
  "git.enableSmartCommit": true,
  "editor.fontLigatures": true,
  "workbench.colorCustomizations": {
    "[Tokyo Night]": {
      "editor.selectionBackground": "#3D59A1",
      "editor.selectionHighlightBackground": "#3D59A1"
    }
  },
  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": "entity.name.function",
        "settings": {
          "foreground": "#47daff", // Couleur de la méthode
          "fontStyle": "bold" // Style de la police (bold, italic, underline)
        }
      },
      {
        "scope": "storage.type",
        "settings": {
          "foreground": "#ebded9" // Choisissez une couleur si vous le souhaitez
        }
      },
      {
        "scope": "support.type",
        "settings": {
          "fontStyle": "bold",
          "foreground": "#fadf4a" // Choisissez une couleur si vous le souhaitez
        }
      }
    ]
  },
  "multiCommand.commands": {
    "command": "multiCommand.makeRoom",
    "Sequence": [
      "workbench.action.tooggleSidebarVisibility",
      "workbench.action.toggleActivityBarVisibility"
    ]
  },
  "gitlens.currentLine.enabled": false,
  "gitlens.codeLens.enabled": false,
  "gitlens.hovers.currentLine.over": "line",
  "git.autofetch": true,
  "conventionalCommits.lineBreak": "\\n",
  "[javascript]": {
    "editor.defaultFormatter": "vscode.typescript-language-features"
  },
  "[html]": {
    "editor.defaultFormatter": "vscode.html-language-features"
  },
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[vue-directives]": {},
  "[vue]": {
    "editor.defaultFormatter": "cweijan.vetur-plus"
  },
  "[php]": {
    "editor.defaultFormatter": "DEVSENSE.phptools-vscode"
  },
  "workbench.productIconTheme": "a-file-icon-vscode-product-icon-theme",
  "workbench.iconTheme": "a-file-icon-vscode",
  "[blade]": {
    "editor.defaultFormatter": "shufo.vscode-blade-formatter"
  },
  "diffEditor.ignoreTrimWhitespace": false,
  "[dart]": {
    "editor.formatOnSave": true,
    "editor.formatOnType": true,
    "editor.rulers": [80],
    "editor.selectionHighlight": false,
    "editor.suggest.snippetsPreventQuickSuggestions": false,
    "editor.suggestSelection": "first",
    "editor.tabCompletion": "onlySnippets",
    "editor.wordBasedSuggestions": "off"
  },
  "editor.wordWrap": "on",
  "editor.minimap.enabled": false,
  "gitlens.graph.experimental.minimap.enabled": true,

  "workbench.editor.enablePreview": false,
  "[xml]": {
    "editor.defaultFormatter": "DotJoshJohnson.xml"
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "gitlens.advanced.messages": {
    "suppressLineUncommittedWarning": true
  },
  "[css]": {
    "editor.defaultFormatter": "svipas.prettier-plus"
  },
  "workbench.startupEditor": "none",
  "[markdown]": {
    "editor.defaultFormatter": "DavidAnson.vscode-markdownlint"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "terminal.integrated.defaultProfile.windows": "Command Prompt",
  "phpTools.language": "fr",
  "explorer.fileNesting.patterns": {
    "*.ts": "${capture}.js",
    "*.js": "${capture}.js.map, ${capture}.min.js, ${capture}.d.ts",
    "*.jsx": "${capture}.js",
    "*.tsx": "${capture}.ts",
    "tsconfig.json": "tsconfig.*.json",
    "package.json": "package-lock.json, yarn.lock, pnpm-lock.yaml, bun.lockb",
    "*.sqlite": "${capture}.${extname}-*",
    "*.db": "${capture}.${extname}-*",
    "*.sqlite3": "${capture}.${extname}-*",
    "*.db3": "${capture}.${extname}-*",
    "*.sdb": "${capture}.${extname}-*",
    "*.s3db": "${capture}.${extname}-*"
  },
  "window.menuBarVisibility": "compact",
  "workbench.sideBar.location": "right",
  "workbench.editor.editorActionsLocation": "titleBar",
  "editor.stickyScroll.enabled": false,
  "workbench.colorTheme": "One Dark Pro Mix",
  "workbench.editorAssociations": {
    "*.html": "default"
  }
}
