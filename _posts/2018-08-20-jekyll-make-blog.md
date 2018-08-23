---
layout: post
title: "Jekyll로 블로그 만들기"
subtitle: "너도 나도 할 수 있는 블로그"
date: 2018-08-20 00:00:00
background: '/img/bg-post.jpg'
category: jekyll/blog
---

홈페이지를 만들기 위한 작업을 기록합니다.

```yaml
 title: ruvieye's blog
 email: ruvieye@naver.com
 description: Continuous devlog
 author: ruvieye
 baseurl: ""
 url: "http://ruvieye.github.io"

 # Social Profiles
 twitter_username:  ruvieye
 github_username:   ruvieye
 facebook_username: ruvieye

 # Build settings
 markdown:          kramdown
 paginate:          7
 paginate_path:     "/posts/page:num/"
 plugins:
   - jekyll-feed
   - jekyll-paginate
   - jekyll-gist

```

{% gist c08ee0f2726fd0e3909d %}

