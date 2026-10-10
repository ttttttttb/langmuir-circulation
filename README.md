# 朗缪尔环流（Langmuir Circulation）

物理海洋学教学用单页科普站点：用表格与手绘 SVG 剖面图解释朗缪尔环流的定义、尺度、生成机制（Craik–Leibovich 涡力）、流场特征与效应。

- **在线地址**：https://ttttttttb.github.io/langmuir-circulation/
- **本地预览**：双击 `index.html`，或在本目录执行 `npx serve .`
- **技术实现**：单文件 HTML + 内联 CSS + 手绘 SVG；无外部依赖、无构建流程、可离线打开
- **源文件出处**：由 `outputs/朗缪尔环流.html` 拷贝而来（SHA256 一致）；此后本目录的 `index.html` 为线上唯一来源

## 目录结构

```
index.html   页面本体（即站点根路径）
.nojekyll    关闭 Jekyll 处理，按纯静态发布
README.md    本文件
```

## 更新方式

```bash
git add -A
git commit -m "更新说明"
git push
```

推送后 1–2 分钟内 GitHub Pages 自动更新。

## 回滚

删除 GitHub 上的仓库即可下线站点；本地删除本目录即可。
