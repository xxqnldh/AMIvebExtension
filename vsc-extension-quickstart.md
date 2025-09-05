# 欢迎使用 VS Code 扩展

## 文件说明

* 此文件夹包含扩展所需的全部文件。
* `package.json` - 扩展清单文件，声明语言支持并定义语法文件位置。
* `syntaxes/veb_001.tmLanguage.json` - TextMate 语法文件，用于分词和高亮。
* `language-configuration.json` - 语言配置文件，定义注释和括号等规则。

## 快速开始

* 确认 `language-configuration.json` 配置正确。
* 按 `F5` 以调试模式启动扩展。
* 新建 `.veb` 文件，检查语法高亮和注释等功能。

## 修改扩展

* 修改上述文件后，可在调试工具栏重新启动扩展。
* 也可通过 `Ctrl+R`（或 Mac 上的 `Cmd+R`）刷新窗口加载新内容。

## 增加更多语言特性

* 如需添加智能提示、悬停、校验等功能，请参考 VS Code 扩展开发文档：https://code.visualstudio.com/api/language-extensions/overview

## 安装扩展

* 将扩展复制到 `<用户目录>/.vscode/extensions` 文件夹并重启 VS Code 即可使用。
* 发布扩展请参考：https://code.visualstudio.com/api/working-with-extensions/publishing-extension
* To share your extension with the world, read on https://code.visualstudio.com/api/working-with-extensions/publishing-extension about publishing an extension.
