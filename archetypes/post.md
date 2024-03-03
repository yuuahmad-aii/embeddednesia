---
date: '{{ .Date }}'
draft: true
title: '{{ replace .File.ContentBaseName `-` ` ` | title }}'
description: tulis deksripsi singkat postingan anda disini
# image: cover.jpg
math: true
license: 
hidden: false
comments: true
draft: false
categories:
    # - Example Category
tags:
    # - Example Tag
# weight: 1       # You can add weight to some posts to override the default sorting (date descending)
---