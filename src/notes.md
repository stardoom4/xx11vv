---
layout: base.njk
title: Notes
permalink: /notes/
---
{%- for post in collections.wiki %}
* [{{ post.data.title }}]({{ post.url }})
{%- endfor %}
