# whydizhi

私人网址导航站（加密访问）。

## 本仓库内容

- `index.html` — AES-256-GCM 加密的站点页面，浏览器端输入密码解密展示
- `.nojekyll` — 禁用 Jekyll，按静态文件服务
- `README.md` / `.gitignore` — 说明与安全网（忽略明文与脚本，防止误提交）

**本仓库只存放加密产物。** 明文内容、构建脚本与使用说明均保存在私有仓库，不在此处。

## 部署（GitHub Pages）

仓库 Settings → Pages → Source 选 `main` 分支 `/ (root)`。
公开访客只能看到密文，输入密码后浏览器端解密展示。
