 ### vscode 配置vue eslint 自动保存
```
        {
            "files.autoSave": "onFocusChange",
            "editor.fontSize": 14,
            "editor.wordWrap": "wordWrapColumn",
            "editor.wordWrapColumn": 120,
            "eslint.validate": [
                "javascript",
                "typescript",
                {
                    "language": "vue",
                    "autoFix": true
                },
                "html",
                "vue"
            ],
            "emmet.syntaxProfiles": {
                "vue-html": "html",
                "vue": "html"
            },
            "eslint.autoFixOnSave": true,
            "eslint.alwaysShowStatus": true,

            "explorer.confirmDelete": false,
            "javascript.updateImportsOnFileMove.enabled": "always",
            "window.zoomLevel": 0,
            "liveServer.settings.CustomBrowser": "chrome",
            "liveServer.settings.donotShowInfoMsg": true,
            "workbench.startupEditor": "welcomePage",
            "git.autofetch": true,
            "diffEditor.ignoreTrimWhitespace": true,
            "diffEditor.renderSideBySide": false,
            "files.associations": {
                "*.vue": "vue",
                "*.cjson": "jsonc",
                "*.wxss": "css",
                "*.wxs": "javascript"
            },
            "emmet.includeLanguages": {
                "wxml": "html"
            },
            "minapp-vscode.disableAutoConfig": true,
            "turboConsoleLog.quote": "'",
            "commentTranslate.multiLineMerge": true,
            "editor.suggestSelection": "first",
            "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
        }
```