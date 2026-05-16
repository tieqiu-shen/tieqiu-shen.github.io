---
layout: default
title: Blog
---

# Blog

{% for post in site.posts %}
## [{{ post.title }}]({{ post.url | relative_url }})

{{ post.date | date: "%Y-%m-%d" }}

{{ post.excerpt }}

{% endfor %}