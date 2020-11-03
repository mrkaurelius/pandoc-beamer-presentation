---
title: Easy Markdown to Beamer with Pandoc
subtitle: Simple things nobody tells you how to do
author: Ahmet Mehmetoglu
date: 2020 
theme: Dresden
colortheme: default
institute: "My home office"
section-titles: false
fontsize: 10pt
---

# Tools

## Subsection 1

### What is this
* Do not need anything else than markdown
    * Slides title starts with # (also starts a new slide)
    * Bullet points, newlines, empty lines: all standard markdown
* However, can also use other stuff, e.g.:
    * Some HTML (e.g. \<center\>)
    * When using pandoc beamer, can use latex commands (e.g. \\center, \\large, etc)\dots

### Formating 
```C
printf("merhaba yalan dunya");
```

\center The slide syntax is so simple that you can quickly create a handful of slides on basically any device in any editor. E.g. on your mobile on the way to the meeting where you need the slides. Right before the meeting starts you use pandoc to create the actual slides from your source.


### Formatting
#### Table
| Right | Left | Default | Center |
|------:|:-----|---------|:------:| 
|  12   |  12  |  12     |   12   | 
| 123   |  123 |   123   |  123   | 
|   1   |    1 |     1   |    1   | 
|   1   |    1 |     1   |    1   | 
|   1   |    1 |     1   |    1   | 
|   1   |    1 |     1   |    1   | 

### Formatting
#### This is a block!

- Here is some content.
- Here's more contents.

---


### Sources 
* https://geekoverdose.wordpress.com/2018/12/10/2628/
* https://qiita.com/kimagure/items/9d27015e12d4f22b53db

