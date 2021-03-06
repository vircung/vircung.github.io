---
layout: post
title: Technical decisions about my blog
cover: /assets/pexels/pexels-photo-388241.jpeg
cover-meta: https://www.pexels.com/photo/black-and-white-blur-close-up-fingers-388241/
tags:
  - en
---

Another thing that I was thinking about while deciding that I will bet back to writing was how this should be hosted. There was few possibilities that I was considering. One of them was self-hosted Wordpress. This would give most possibilities of configuration and integrating already created solutions and plugins if needed. And I know this would eat up a lot of time for me to set up everything before I write some articles.

<!-- more -->

Bloging services
---

Another possibility would be those some services like [Medium](https://medium.com/@vircung) that gives hassle-free writing experience together with good looking layout. Flip side of this approach is lack of possibility of configuring it to my needs and taste. And I don't like it that way. Similar thing is about other ones that are widely used by newcomers like [Wordpress.org](https://wordpress.org) or [Blogspot](https://blogspot.com/) that I've at least tried once. They are good for starters that want to try if writing is for them and that's good.

I like to have full control of my creations and ownership of them. Which is not fully possible with any non-self-hosted service. None of them gives that ability because all of them can remove content that I've created for any reason and they also want to have ownership of if. I don't like it so I won't choose them. Time to move on to more "advanced" solutions.

Self-hosted things
---

For self-hosted solutions I was trying to decide between another two, [Ghost](https://ghost.org) or [Jekyll](https://jekyllrb.com) hosted on [Github Pages](https://pages.github.com). Ghost is pretty much simply solution, pleasing for an eye to look at and there is possibility for extending it functionalities as needed. On the other had it's pretty early for it as a project and development of it slowed pretty much which is not conforming me that much.

Whats more it requires full server running and to be maintained in case of any downtimes or breaking in. Of course possibility of someone trying to hack in on the server is small. Having experience with server running only [IRC bounceer](https://github.com/vircung/docker-znc) and being shut down due to suspiciously large traffic is nothing that I want to rely on my blog right now. Probably in future when my needs will become more demanding.

Chosen solution
---

Given that above I decided to still stay with Jekyll. It's static web site generator that works with Github. For me currently is good compromise between complexity of full fledged solutions like Wordpress, simplicity of bloging services and having control over content and whole site. As a bonus feature anyone can contribute to those articles and page itself if there are any typos, inconsistencies, improvements to be made, mistakes or I was just wrong.

Of course hosting it as Github Page reduces possibilities which gives Jekyll but on other hand moving it to other hosting solution like FTP or AWS S3 bucket is pretty much simple. For that reason I generate backup of whole page ready to quickly switch target solution.
