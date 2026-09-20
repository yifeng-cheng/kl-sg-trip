KL·SG Trip 2026 — iPhone PWA

重要：真正以“网页 App”方式安装，需要把整个文件夹部署到 HTTPS 网站；直接从 iPhone“文件”App打开 index.html 只能当普通离线网页使用，Service Worker/PWA 安装能力不会完整工作。

最简单部署方法之一：
1. 把本文件夹全部上传到任意支持 HTTPS 的静态网站托管服务。
2. 用 iPhone Safari 打开部署后的 index.html 地址。
3. Safari → 分享 → 添加到主屏幕 → 开启“作为网页 App 打开” → 添加。
4. 首次联网打开一次后，核心页面由 Service Worker 缓存，可离线查看；地图导航和外部官网仍需网络。

交互状态（已完成、已吃、已预约等）保存在 iPhone 本机浏览器 localStorage 中。

当前仍需最终确认：Venue Hotel 的具体分店/完整地址；携程“海洋馆+环球”具体 SKU 是否允许 10/4 与 10/5 跨日使用。
