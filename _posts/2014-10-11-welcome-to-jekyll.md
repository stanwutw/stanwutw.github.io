---
layout: post
title:  "Jekyll 讓程式開發與文件撰寫融合在一起"
date:   2014-10-11 21:20:18
categories: jekyll update
---

![logo](http://jekyllrb.com/img/logo-2x.png)

# 懶人的最愛

如果您跟我一樣 *不喜歡移動您的雙手, 最好是一直都貼在鍵盤上面動動手指就好* , 
很少移動游標, 幾乎都是用熱鍵或是CLI命令介面, 那麼我相信您也會愛上[Jekyll][jekyll]

# 寫文章跟寫程式其實是同一件事情

寫文章其實跟寫程式基本上是同一件事情, 跟程式撰寫比起來寫其實文章更難, 程式寫錯了
產生 bug 引起當機, 重新開機就好, 文章用字表達錯了, 引起不必要的誤會, 麻煩就大了
所以文章寫的好, 程式自然寫的也不差, 但是開 Word 寫文件, 又要開 IDE 寫程式真的
很麻煩, 現在只要使用 [Sublime Text][sublime] 配合 [Jekyll][jekyll] 就可以
簡單的同時完成兩件事情

![sublime](http://d2o0t5hpnwv4c1.cloudfront.net/1140_st2plugins/codeintel.png)

# 如何發佈一個新的文章

You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve --watch`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll’s dedicated Help repository][jekyll-help].

[jekyll]:      http://jekyllrb.com
[sublime]:	   http://www.sublimetext.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help
