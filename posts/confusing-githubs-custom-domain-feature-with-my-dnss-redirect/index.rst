.. title: Confusing github's custom domain feature, with my dns's redirect
.. slug: confusing-githubs-custom-domain-feature-with-my-dnss-redirect
.. date: 2021-03-24 23:01:03 UTC-07:00
.. tags: blog
.. category: blog
.. link: 
.. description: How inept at networks am I?
.. type: text

So github has this handy setting for github pages that will redirct your repo's or user's github.io page to some other server. But my dumb ass misread that and thought it was a setting to point my custom hostname at the github page and like, it needed to know what url was going to be redirecting to it for permissions or some such. But no it was a CNAME redirect.. meaning that when I went to my domain registar and pointed my custom domain at the github.io url I created a loop.I need to find some good books on that stuff at some point. 
