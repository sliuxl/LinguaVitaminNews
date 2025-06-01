---
layout: default
title: Home
---

Welcome to **LinguaVitamin News**!
Here you’ll find daily multilingual news to boost your language learning.

- Source code: [LinguaVitaminNews](https://github.com/sliuxl/LinguaVitaminNews)
- Read arXiv papers instead: [https://sliuxl.github.io/LinguaVitaminArxiv](https://sliuxl.github.io/LinguaVitaminArxiv)

---

## 📰 Latest Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a><br />
      <small>{{ post.date | date: "%Y-%m-%d" }}</small>
    </li>
  {% endfor %}
</ul>
