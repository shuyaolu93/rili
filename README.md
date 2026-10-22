# Rili 事件日历

Rili 是一个面向投资研究的中文事件日历，展示未来两周事件，统一使用北京时间，并自动更新。

在线网址：<https://rili-investment-calendar.chicseal1024.chatgpt.site/>

## 内容

- 未来两周事件日程
- 北京时间显示
- 日期导航：点击日期查看当天事件
- 事件重要性标注：高 / 中 / 低
- 实际值和预期值分别展示
- Cloudflare Worker 提供自动刷新和缓存

## 目录

- `dist/index.html`：网页页面
- `worker/index.js`：Cloudflare Worker 后端
- `.openai/hosting.json`：在线站点配置
