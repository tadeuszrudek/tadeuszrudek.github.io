---
title: "News"
layout: gridlay
sitemap: false
permalink: /allnews.html
---

## News

<div class="section-card" markdown="0">
<div class="news-timeline">
{% for post in site.posts %}
<div class="news-item">
<span class="news-date">{{ post.date | date: "%b %-d, %Y" }}</span>
<span class="news-headline"><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></span>
</div>
{% endfor %}
</div>
</div>