# OneLinks - 链接聚合页面

一个使用原生 HTML + CSS + JS 制作的链接聚合页面，类似于 Linktree 的功能，用于在一个页面上集中展示多个社交媒体链接和个人资源链接。

## 预览

![demo](preview.png)

## 特性

- 🚀 **纯静态页面**：无需后端支持，可部署到任何静态托管服务
- 🎵 **集成音乐播放器**：内置 APlayer 和 MetingJS，支持在线音乐播放
- 📱 **响应式设计**：适配各种设备屏幕尺寸
- 🎨 **简洁美观**：现代化 UI 设计，用户体验友好
- ⚡ **快速加载**：轻量级实现，加载速度快
- 🔧 **易于自定义**：结构清晰，便于个性化定制
- 📝 **支持添加博客文章**：只需编写 Markdown 文章，即可渲染展示。

## 安装与使用

### 本地运行

1. 克隆或下载此仓库到本地，ssh命令：`git clone https://github.com/yunliyo/onelinks.git`；
2. 修改文字、图片等资源文件；
3. 进入项目目录并直接在浏览器中打开 `index.html` 文件即可预览。

### 部署到线上

您可以将此项目部署到以下静态网站托管服务：

- GitHub Pages
- Netlify
- Vercel
- Cloudflare Pages
- 服务器部署

## 配置

### 基本配置

1. 修改 `index.html` 和 `i.html` 文件：
2. 修改 `/assets/` 文件夹下的资源文件。

### 音乐播放器配置

位于 `assets/player/` 目录下的播放器支持以下音乐平台：

- NetEase Cloud Music (网易云音乐)
- QQ Music (QQ音乐)
- KuGou Music (酷狗音乐)
- MyPlaylist (自定义歌单)

可在 `assets/js/script.js` 中配置播放器参数。

## 自定义

### 样式调整

- 主要样式文件：`assets/css/i.css` 和 `assets/css/style.css`；
- 可以修改颜色、字体、间距等视觉元素

### 添加新功能

- JavaScript 逻辑：`assets/js/script.js` 和 `assets/js/c.js`；
- 可以扩展新的交互功能

## 技术栈

- **HTML5**: 页面结构
- **CSS3**: 样式与动画
- **JavaScript ES6+**: 交互逻辑
- **APlayer**: 音乐播放器组件
- **MetingJS**: 音乐 API 对接
- **HLS.js**: HTTP Live Streaming 支持

## 文件结构

```
onelinks/
├── assets/
│   ├── css/
│   │   ├── style.css      # 样式
│   │   └── i.css          # 主样式
│   ├── js/
│   │   ├── script.js      # 脚本
│   │   └── c.js           # 主脚本
│   └── player/            # 音乐播放器相关文件
│       ├── css/
│       │   └── APlayer.min.css
│       └── js/
│           ├── APlayer.min.js
│           ├── Meting.min.js
│           ├── hls.min.js
│           └── setting.js
├── page/                  # 文章页面模块
│   ├── articles/          # 文章页面存放目录
│   │   ├── about/         # 页面一
│   │   ├── garden/        # 页面二
│   │   └── introduction/  # 页面三
│   ├── assets/            # 文章页资源
│   │   ├── css/           # 文章页样式
│   │   └── js/            # 文章页脚本
│   └── index.html         # 文章页入口
├── blog/                  # 基于 Docsify 搭建的简易博客
├── docs/                  # 基于 Docute 搭建的简易文档
│   ├── note/              # 文档一
│   └── notion/            # 文档二
├── index.html             # index 主页入口
├── i.html                 # 主页面
├── README.md              # 项目说明
```

## 贡献

欢迎提交 Issue 和 Pull Request 来改进此项目！

## 许可证

MIT License

## 致谢

- [APlayer](https://github.com/MoePlayer/APlayer) - HTML5 音乐播放器
- [MetingJS](https://github.com/metowolf/MetingJS) - 音乐 API 接口
- [Linktree](https://linktr.ee/) - 设计灵感来源
