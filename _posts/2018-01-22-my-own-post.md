---
layout: post
title:  "Updating My Own Post"
date:   2018-01-22
categories: [ one, two, three ]
---

## Apply your markdown knowledge!

{% for category in page.categories %}
 {{ category }}
{% endfor %}

# Testing with Header 1


## Testing with Header 2 

**bold**

*italics*

__underscore__

1. Actual numbers don't matter, just that it's a number

⋅⋅1. Ordered sub-list
4. And another item.

⋅⋅* Unordered sub-list.

Creating a new [link](http://bbc.co.uk)

![Picture 1](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

