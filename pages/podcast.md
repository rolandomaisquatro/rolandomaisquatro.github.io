---
layout: page
show_meta: false
title: "Podcasts do Rolando +4"
header:
    image_fullwidth: FundoBlog.png
permalink: "/podcast/"
---
<ul>
    {% for post in site.categories.rolando-mais-quatro %} 
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>

<ul>
