---
layout: default
---

<body>
  <div class="index-wrapper">
    <div id="aside" class="aside">
      <div class="info-card">
        <h1>智若雨</h1>
        <a href="https://www.weibo.com/m_convert" target="_blank"><img src="https://www.weibo.com/favicon.ico" alt="" width="25"/></a>
        <a href="https://www.douban.com/people/179274556/" target="_blank"><img src="https://www.douban.com/favicon.ico" alt="" width="22"/></a>
        <a href="https://instagram.com/beiyuu/" target="_blank"><img src="https://d36xtkk24g8jdx.cloudfront.net/bluebar/00c6602/images/ico/favicon.ico" alt="" width="22"/></a>
      </div>
      <div id="particles-js"></div>
    </div>

    <div class="index-content">
      <ul class="artical-list">
        {% for post in site.categories.blog %}
        <li>
          <a href="{{ post.url }}" class="title">{{ post.title }}</a>
          <div class="title-desc">{{ post.description }}</div>
        </li>
        {% endfor %}
      </ul>
    </div>
  </div>
</body>
