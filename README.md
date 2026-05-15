# Nexus Demo 集合

Nexus 项目汇报中拆分出的可独立访问的交互 Demo，便于嵌入到腾讯文档 / 飞书 / Notion 等。

## 在线访问

- 索引页：`index.html`
- ① 工具提升（A/B/C 三项 AI 能力）：`tool-improvement.html`
- ② 管理层话题全链路 Demo（5 步走）：`mgmt-topic-demo.html`

## 内嵌方法

### 方法 1：直接贴链接（推荐）
在腾讯文档 / 飞书 / Notion 中直接粘贴部署后的 GitHub Pages 链接。

### 方法 2：iframe 嵌入（Notion/Confluence 支持）
```html
<iframe src="https://<user>.github.io/<repo>/tool-improvement.html" width="100%" height="900px" frameborder="0"></iframe>
```

### 方法 3：截图 / 录屏（任意文档）
浏览器打开后用截图工具或录屏插件抓取交互过程，插入文档。

## 文件清单

| 文件 | 说明 |
|---|---|
| `index.html` | 索引页（Demo 集合入口） |
| `tool-improvement.html` | 工具提升 · 三项 AI 能力交互 Demo |
| `mgmt-topic-demo.html` | 管理层话题全链路 5 步走 Demo |
| `README.md` | 本文件 |

## 维护

源文件位于 `AI总结优化方案/28_Nexus汇报.html`，本目录为拆分后的独立可分发版本。
