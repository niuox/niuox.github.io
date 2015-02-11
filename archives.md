---
layout: page
title: Archives
permalink: /archives/
---

<div class="home">
    {% for post in site.posts %}
	     <p style="font-size:20px"><a class="" href='{{post.url}}'>{{post.title}}</a>
		<span class="post-meta"> {{ post.date | date: "%b %-d, %Y" }} </span></p>
    {% endfor %}
</div>