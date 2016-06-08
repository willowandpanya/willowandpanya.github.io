---
layout: post
title:  "First Post"
date:   2016-06-08 13:43:24 -0700
categories: oils site
image: /images/tubes_example.jpg
---
Welcome to the site, this is your first post. Generally the first paragraph of the post will appear above the fold on the front page. So make sure the first few lines really draw the reader in.

If you want to learn formatting for the Markdown language (which this post is
written in) see here: [markdown_cheatsheet.pdf](http://scottboms.com/downloads/documentation/markdown_cheatsheet.pdf)

For a quick tutorial, just search google for "markdown tutorial" and you should
be on your way.

Adding images is a little trickier, but basically you just upload the image
into the images directory. Then specify the path as `/images/my_image_name.jpg`

The image declaration looks like this:

    ![alt text](/images/my_image_name.jpg)

You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
