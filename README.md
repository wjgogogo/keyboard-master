# keyboard-master

一套以键盘为核心的高效工作流配置，帮助程序员提升编码效率，减少对鼠标的依赖。

## 项目介绍

本项目收集了各种提升键盘使用效率的软件、插件和配置文件，主要包括：

- **VSCode 编辑器**：快捷键配置和 Vim 模式使用
- **浏览器导航**：通过扩展实现键盘控制网页浏览
- **辅助软件**：键位映射、输入法切换、窗口管理等

> 配置以 macOS 系统为准，详细使用说明请查看 [键盘效率提升指南（VSCode+Vim+SurfingKeys）](https://mp.weixin.qq.com/s/oVg6mCeCtrJzY5-CLRQRNA) 文档。

## 软件推荐

### 核心软件

| 软件                   | 说明                                   | 官网                                         |
| ---------------------- | -------------------------------------- | -------------------------------------------- |
| **Karabiner-Elements** | 强大的键位修改软件，支持复杂的键位映射 | [官网](https://karabiner-elements.pqrs.org/) |
| **VSCode**             | 现代化代码编辑器，支持丰富的插件生态   | [官网](https://code.visualstudio.com/)       |
| **Raycast**            | Alfred 的替代品，免费且功能强大        | [官网](https://www.raycast.com/)             |

### 浏览器扩展

| 扩展            | 说明                                    | 商店链接                                                                                                  |
| --------------- | --------------------------------------- | --------------------------------------------------------------------------------------------------------- |
| **SurfingKeys** | Chrome Vim 模式插件，实现键盘控制浏览器 | [Chrome Web Store](https://chromewebstore.google.com/detail/surfingkeys/gfbliohnnapiefjpjlpjnehglfpaknnc) |

### 窗口管理

| 软件          | 说明                                      | 官网                                       |
| ------------- | ----------------------------------------- | ------------------------------------------ |
| **Rectangle** | 窗口位置移动、大小调整的键盘操作工具      | [官网](https://rectangleapp.com/)          |
| **AltTab**    | 改善 Mac 应用切换体验，自动打开最小化应用 | [官网](https://alt-tab-macos.netlify.app/) |

### 输入法管理

| 软件                 | 说明                                | 官网                                              |
| -------------------- | ----------------------------------- | ------------------------------------------------- |
| **Input Source Pro** | 为不同软件设置默认输入法，自动切换  | [官网](https://inputsource.pro/zh-CN)             |
| **im-select**        | 命令行输入法切换工具，配合 Vim 使用 | [GitHub](https://github.com/daipeihust/im-select) |

## VSCode 插件

### Vim 相关

| 插件               | 说明                                          | 商店链接                                                                                           |
| ------------------ | --------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| **Vim**            | VSCode 中的 Vim 模式插件，提供完整的 Vim 体验 | [Marketplace](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim)                   |
| **VSCode Neovim**  | 集成 NeoVim，提供更接近原生 Vim 的体验        | [Marketplace](https://marketplace.visualstudio.com/items?itemName=asvetliakov.vscode-neovim)       |
| **Learn Vim**      | 交互式 Vim 学习插件                           | [Marketplace](https://marketplace.visualstudio.com/items?itemName=vintharas.learn-vim)             |
| **Vim Cheatsheet** | Vim 按键说明插件                              | [Marketplace](https://marketplace.visualstudio.com/items?itemName=AndenetAlexander.vim-cheatsheet) |

### 代码编辑

| 插件               | 说明                                     | 商店链接                                                                                  |
| ------------------ | ---------------------------------------- | ----------------------------------------------------------------------------------------- |
| **Surround**       | 代码包裹插件，快速添加括号、引号、标签等 | [Marketplace](https://marketplace.visualstudio.com/items?itemName=yatki.vscode-surround)  |
| **GitLens**        | Git 增强插件，提供代码历史和协作功能     | [Marketplace](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)        |
| **Toggle Boolean** | 快速切换布尔值、状态等                   | [Marketplace](https://marketplace.visualstudio.com/items?itemName=silesky.toggle-boolean) |
| **Bookmarks**      | 代码书签管理，快速标记和跳转             | [Marketplace](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks)  |
| **Prettier**       | 代码格式化工具，保持代码风格一致         | [Marketplace](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) |

## .vscode 配置文件

本项目包含以下 VSCode 配置文件：

### `settings.json`
VSCode 的用户设置文件，包含：
- **Vim 基础配置**：Leader 键、相对行号等
- **插件配置**：Sneak、EasyMotion、Surround 等
- **输入法配置**：自动切换输入法设置
- **编辑器配置**：行号显示、键盘重复等

### `keybindings.json`
VSCode 的键盘快捷键配置文件，包含：
- **文件操作**：快速创建、重命名、删除文件
- **面板切换**：设置面板与 JSON 文件的快速切换
- **全局搜索**：搜索结果的键盘导航
- **Git 操作**：版本控制的快捷操作
- **终端操作**：终端的创建、切换、关闭
- **悬停操作**：代码悬停信息的键盘控制

### `extensions.json`
VSCode 的推荐扩展配置文件，包含：
- **Vim 插件**：vscodevim.vim
- **代码编辑**：yatki.vscode-surround、silesky.toggle-boolean
- **代码管理**：eamodio.gitlens、alefragnani.Bookmarks
- **代码格式化**：esbenp.prettier-vscode
