---
layout: default
title: "招聘信息"
---

{% for post in site.categories.jobs %}
  <div class="post">
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    <p>{{ post.excerpt }}</p>
  </div>
{% endfor %}