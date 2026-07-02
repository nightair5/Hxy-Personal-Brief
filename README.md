# 黄雄业 AI 产品运营 / Agent 产品运营个人主页

这是一个面向 GitHub Pages 部署的单页静态个人主页，定位为 **AI 产品运营 / Agent 产品运营 / AIGC 内容产品** 方向。

## 页面结构

1. Home / 顶部个人信息与求职方向
2. 个人优势摘要
3. 教育背景
4. AI 相关运营能力
5. AI 项目与作品经历
6. 代表项目经历
7. 组织实践与内容运营
8. 工具栈
9. More Works / 综合作品
10. 联系我

## 部署文件

GitHub Pages 只需要以下文件：

- `index.html`
- `.nojekyll`
- `README.md`
- `assets/huang-xiongye-ai-product-agent-resume.docx`
- `assets/profile.webp`
- `assets/aigc-nangying-closeup.webp`
- `assets/project-qianwen.webp`
- `assets/project-xiaofulong.webp`
- `assets/project-textbook-drift.webp`
- `assets/project-campus-video.webp`
- `assets/project-gourmet-map.webp`
- `assets/project-journaliststi.webp`
- `assets/project-operator-dilemma.webp`
- `assets/project-tailme.webp`
- `assets/photo-xiamen-5am.webp`
- `assets/photo-monochrome-sea.webp`
- `assets/photo-night-tide.webp`
- `assets/photo-afterglow.webp`

## 本地预览

```bash
python -m http.server 8000 --bind 127.0.0.1
```

打开：

```text
http://127.0.0.1:8000/
```

## GitHub Pages

仓库地址：

```text
https://github.com/nightair5/Hxy-Personal-Brief
```

本仓库包含 GitHub Actions 部署工作流：

```text
.github/workflows/pages.yml
```

如果仓库 Actions 与 Pages 权限正常，推送到 `main` 后会自动部署；工作流会尝试在首次运行时启用 Pages。若首次访问仍是 404，可在 GitHub 仓库中检查：

- `Settings` → `Pages`
- Source 选择 `GitHub Actions`
- 保存后重新运行 `Deploy static site to Pages`

部署后通常访问：

```text
https://nightair5.github.io/Hxy-Personal-Brief/
```
