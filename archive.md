---
layout: page
title: Archive
---

##### Blog Posts

{% assign openpar = "<p>" %}
{% assign closepar = "</p>" %}

{% for post in site.posts %}
 * {{ post.date | strip_html | date_to_string }} &raquo; [ {{ post.title }} ]({{ post.url }})
{% endfor %}
