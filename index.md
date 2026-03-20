---
layout: default
title: 首页
---

欢迎来到我的博客，这里分享：

- Google生态（Gmail / Google Voice / YouTube / Gemini）
- Apple生态（Apple ID / iCloud+ / 礼品卡）
- AI工具（ChatGPT / Gemini / Claude）
- 数字礼品卡与账号资源
- 出海工具与跨境实用经验

---

## 最新文章

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <small>（{{ post.date | date: "%Y-%m-%d" }}）</small>
    </li>
  {% endfor %}
</ul>
