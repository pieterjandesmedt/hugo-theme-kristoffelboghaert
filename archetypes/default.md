---
title: {{ .Name | replaceRE "[_-]" " "  | replaceRE "^[0-9]+" "" | title }}
date: {{ .Date }}
author: Kristoffel Boghaert
banner: image0.jpg
images:
- image1.jpg
- image2.jpg
---

Summary or first few lines of the article goes here.

<!--more-->

Here comes the rest of the article.

### Title

#### Subtitle

**bold**

_italic_

&nbsp;|&nbsp;
------|------
table	|		with columns

> A quote

[a link](https://www.google.com)

