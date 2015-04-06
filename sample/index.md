---
layout: archive
title: "Sample"
date: 
modified:
excerpt:
image:
  feature:
  teaser:
  thumb:
ads: false
---

A page to showcase things or have a series of pages or something. Currently only blog 
posts are being showcased, but you could go creative with these if needed.

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->

