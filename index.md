---
layout: page
title: Memory Leak
---
{% include JB/setup %}

>以此来记录我内心的空洞 时间与世界 绝望与希望...

_ _ _

#### 最近发布的文章：

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
