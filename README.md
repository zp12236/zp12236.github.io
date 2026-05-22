# AI星图（GitHub Pages）

这是一个关于 AI 的静态网页博客，可直接部署到 GitHub Pages。

## 一键发布（已配置）
本仓库已添加 GitHub Actions 工作流：
- 文件：`.github/workflows/deploy-pages.yml`
- 触发分支：`main` / `master` / `work`

### 你需要做的事
1. 把这个仓库推送到 GitHub（确保有远程仓库）。
2. 打开仓库 `Settings` → `Pages`。
3. 在 **Build and deployment** 里选择 **Source: GitHub Actions**。
4. 推送一次代码（或手动运行 Actions 里的 `Deploy static site to GitHub Pages`）。
5. 等待工作流成功后，访问：
   - `https://<你的用户名>.github.io/<仓库名>/`（项目仓库）
   - 或 `https://<你的用户名>.github.io/`（若仓库名就是 `<用户名>.github.io`）

## 本地预览
直接打开 `index.html` 即可预览静态页面。
