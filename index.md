---
layout: page
title: Marios Koniaris
tagline: engineer, researcher, etc.
---
{% include JB/setup %}

<div class="span6 pull-right clearfix">
<a href="archive.html" class="pull-right" style="margin-top:8px">see all...</a>
<h3>News and Blog posts</h3>
<ul class="unstyled">
  {% for post in site.posts limit:20 %}
    <li><span class="muted">{{ post.date | date: "%d.%m.%y" }}</span> <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

<h3>Categories</h3>
<ul class="tag_box inline">
  {% assign categories_list = site.categories %}
  {% include JB/categories_list %}
</ul>
<br />

<h3>Tags</h3>
<ul class="tag_box inline">
  {% assign tags_list = site.tags %}  
  {% include JB/tags_list %}
</ul>
</div>



<img src="assets/images/photo.png" class="img-polaroid span2 pull-right" />

I am a PhD Student, Researcher under the supervision of [Prof. Yannis Vassiliou](http://www.dblab.ntua.gr/people/yv.html), at the 
[School of ECE](http://www.ece.ntua.gr) of the [National Technical University of Athens](http://www.ntua.gr), Greece, and a member of
[Knowledge &amp; Database Systems](http://www.dblab.ntua.gr/) group.


**Research interests.** Information retrieval, network analysis, diversification, web search



