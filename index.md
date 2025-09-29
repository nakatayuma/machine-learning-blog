---
layout: default
title: "Home"
---

# Machine Learning Blog

授業で学んだことをまとめるブログです。

## 最新記事
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span>({{ post.date | date: "%Y-%m-%d" }})</span>
    </li>
  {% endfor %}
</ul>

