---
layout: default
title: "Product"
description: ""
---
{% include JB/setup %}

{% for post in site.posts %}
<hr class="featurette-divider">
<div class="featurette">
<a href="{{ BASE_PATH }}{{ post.url }}"><img class="featurette-image pull-left" src="{{ ASSET_PATH }}Carousel/img/products/{{ post.category }}">
<h2 class="featurette-heading">{{ post.title }} </a></h2>
<p class="lead">{{ post.description }}</p>
</div>
<hr class="featurette-divider">
{% endfor %}
