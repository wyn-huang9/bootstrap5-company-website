# Bootstrap5 响应式企业官网首页
## 项目简介
基于 Bootstrap5.3.3 开发的纯静态企业官网页面，适配电脑、平板、手机多端。
适合前端实习练习，掌握响应式布局、网格系统、组件、工具类、锚点滚动、表单开发。
**无后端接口，全部前端实现，直接浏览器打开运行。**

## 📸项目截图
### PC端整体首页
![PC端首页](./screenshots/home-banner.png)

### 产品卡片板块
![产品卡片](./screenshots/product-card.png)

### 移动端响应式效果
![移动端](./screenshots/mobile-view.png)


## ✨项目特性
1. 导航栏锚点平滑滚动，点击菜单跳转对应页面板块
2. 完整在线留言表单板块，使用bootstrap表单组件
3. 卡片hover悬浮上浮+阴影动画效果
4. 页面滚动显示「回到顶部」按钮
5. 移动端导航自动折叠汉堡菜单
6. 全部图片使用在线占位资源，本地打开无404报错

## 技术栈
- HTML5
- Bootstrap 5.3.3（CDN引入）
- Bootstrap Icons 图标库
- 少量原生JavaScript（回到顶部、导航交互）

## 页面板块结构
1. 导航栏：固定顶部，锚点跳转，移动端折叠汉堡菜单
2. Banner横幅首页区域
3. 核心产品三栏卡片展示
4. 公司简介两栏图文布局
5. 在线留言表单模块【新增】
6. 页脚版权与联系方式

## 核心知识点
1. 网格系统：严格遵循`container > row > col`嵌套；`col-lg‑*`大屏断点响应式
2. 容器区分：
   - `container`：固定宽度，左右留白，内容板块使用
   - `container‑fluid`：100%全屏通栏，适合导航、banner、页脚
3. 工具类：间距`py‑5/mb‑4`，文本居中，弹性布局等，减少手写CSS
4. 组件：navbar导航、card卡片、btn按钮、form表单
5. html原生`scroll‑behavior: smooth`实现平滑滚动
6. 简单原生JS实现回到顶部交互

## 运行方式
1. 下载仓库全部代码
2. 直接双击`index.html`用浏览器打开
3. 缩放浏览器窗口，测试多端响应式效果

## 仓库目录说明
bootstrap5-company-website/
├─ index.html                 # 主项目：Bootstrap5 响应式企业官网首页
├─ README.md                  # 项目说明文档
└─ demo/                      # 课堂练习集合
├─ form-express-demo.html
├─ hobby-card-demo.html
├─ portfolio-demo.html
├─ product-card-demo.html
├─ second-hand-book-index.html
├─ second-hand-book-v2.html
└─ second-hand-login.html
