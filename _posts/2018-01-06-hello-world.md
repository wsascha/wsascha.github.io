---
layout: post
title: Hello World!
excerpt:
categories: [info, code]
comments: false
image:
  feature: https://upload.wikimedia.org/wikipedia/commons/1/1a/Hello_-_Script.svg
  credit: STVN
  creditlink: https://commons.wikimedia.org/wiki/File%3AHello_-_Script.svg
publish: true
---

I decided to create a small blog to share my insights in research and technology to interested people and I hope to do so regularly.
Also expect a couple of things to change as I just created all this.
I am going to make it a lot nicer in the next days!

<!--more-->

As I usually develop things on Ubuntu using C++, let's write a little program that outputs `Hello World!` to the command line.
The file `hello.cpp` could look like this:

{% highlight cpp linenos %}
#include <iostream>
int main() {
  std::cout << "Hello World!" << std::endl;
  return 0;
}
{% endhighlight %}

Using gcc, compiling this file into our program is a one liner:
{% highlight shell %}
~$ g++ hello.cpp -o hello
{% endhighlight %}

Now, our program can be executed from the command line:
{% highlight shell %}
~$ ./hello
Hello World!
{% endhighlight %}

Of course, this program does not really help to do practical things.
However, starting from here, I am going to explain the basics of coding with C++ and also focus on the tools to get stuff done efficiently.

So stay tuned and see you soon!  
