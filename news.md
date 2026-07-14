---
layout: page
title: News
permalink: /news/
---

<ul>
{% for item in site.data.news %}
  <li style="margin-bottom: 10px;">
    <b>{{ item.date }}</b>: {{ item.content }}
  </li>
{% endfor %}
</ul>

<br/>
<br/>


