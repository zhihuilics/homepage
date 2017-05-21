---
layout: post
title: Pictures and movies of random lozenge tilings
date:   2016-08-20 10:00:00
comments: false
categories: blog math simulation
published: true
show-date: true
image: __STORAGE_URL__/img/blog/sauron_eye_tn.png
image-alt: Sauron's eye
more-text: Pictures and movies
img-bulk:
  - web: __STORAGE_URL__/img/blog/card120nonsymm_uniform.png
    alt: Uniformly random tiling of a 9-gon
    size: 1.5 MB
  - web: __STORAGE_URL__/img/blog/card120symm_uniform.png
    alt: Uniformly random tiling of another 9-gon
    size: 1.5 MB
  - web: __STORAGE_URL__/img/blog/hex120_uniform.png
    alt: Uniformly random tiling of a hexagon of height 120
    size: 1.5 MB
  - web: __STORAGE_URL__/img/blog/12gon_uniform.png
    alt: Uniformly random tiling of a 12-gon
    size: 1.5 MB
  - web: __STORAGE_URL__/img/blog/cardgif.gif
    alt: Growth of a tiling of a 9-gon
    size: 6 MB
  - web: __STORAGE_URL__/img/blog/12gif.gif
    alt: Growth of a tiling of a 12-gon (only vertical tiles are shown)
    size: 11 MB
  - web: __STORAGE_URL__/img/blog/12gif_result.png
    alt: Result of the previous simulation
    size: 1.5 MB
  - web: __STORAGE_URL__/img/blog/
    alt: 
    size: 
  - web: __STORAGE_URL__/img/blog/
    alt: 
    size: 
  - web: __STORAGE_URL__/img/blog/
    alt: 
    size: 
  - web: __STORAGE_URL__/img/blog/
    alt: 
    size: 
  - web: __STORAGE_URL__/img/blog/
    alt: 
    size: 
  - web: __STORAGE_URL__/img/blog/
    alt: 
    size: 
  - web: __STORAGE_URL__/img/blog/
    alt: 
    size: 
  - web: __STORAGE_URL__/img/blog/
    alt: 
    size: 
  - web: __STORAGE_URL__/img/blog/
    alt: 
    size: 
---

In Spring 2015 and Summer 2016 I used the Python and Mathematica
as
briefly
described [here]({{site.url}}/2015/02/Glauber-Simulation/)
to produce a number of pictures and "movies" of random lozenge tilings.
Some of these pictures even appeared at an [art exhibition](https://www.radcliffe.harvard.edu/event/2016-art-discovery-exhibition).

These pictures and "movies" of random tilings are collected in this post.

##### Dear colleagues:

Feel free to use these pictures to illustrate your research in talks and papers, with attribution (<a href="https://creativecommons.org/licenses/by-sa/4.0/" target="_blank">CC BY-SA 4.0</a>). Some of the images are available in very high resolution upon request.

<!--more-->


<h2 class="mt-4 mb-3">Links to images &bull; (<a href="{{site.url}}/2016/08/Tilings-examples-inline/" target="_blank">All images in one large page</a>)</h2>

<div class="list-group my-ul-zebra mb-4">
{% for im in page.img-bulk %}
<li class="list-group-item" style="padding:5px 10px">
{{im.size}}&nbsp;&bull;&nbsp;
<a href="{{im.web | replace: '__STORAGE_URL__', site.storage_url }}" target="_blank">{{im.alt}}</a>
</li>
{% endfor %}
</div>