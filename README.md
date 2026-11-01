# 个人研究主页

一个使用纯 HTML、CSS 和 JavaScript 制作的个人研究主页，通过 GitHub Actions 自动发布到 GitHub Pages。无需安装依赖，直接打开 `index.html` 即可预览。

## 启用自动发布

1. 在仓库打开 **Settings → Pages**。
2. 在 **Build and deployment → Source** 中选择 **GitHub Actions**。
3. 将更改推送到 `main` 分支，或在 **Actions → Deploy GitHub Pages** 中选择 **Run workflow**。
4. 等待工作流完成。默认地址为 <https://quiet402.github.io/MainPage/>，实际地址以 Pages 设置和工作流部署结果为准。

以后每次推送到 `main` 都会自动更新主页。部署工作流位于 `.github/workflows/pages.yml`。

## 自定义内容

- `index.html`：修改名字、简介、研究方向、项目和首页文章列表。
- `style.css`：修改配色、排版和响应式样式。
- `posts/hello-world.html`：第一篇示例文章，可修改或复制为新文章；复制后在 `index.html` 的笔记区域添加链接。
- `script.js`：自动更新页脚年份。

当前研究方向为可编辑的栏目说明，并非具体的论文或研究成果。添加个人经历、发表论文或联系方式时，直接替换对应文字和链接即可。
