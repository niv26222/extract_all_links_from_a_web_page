
# Python program to extract all links from a web page using BeautifulSoup 4.



@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
#important !!!!


Activate the virtual env, and then install BeautifulSoup4:

$ pip install BeautifulSoup4



When you installed bs4 with easy_install, you installed it system-wide. So your system python can import it, but not your virtualenv python. If you do not need bs4 to be installed in your system python path, uninstall it and keep it in your virtualenv.

@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@


Beautiful Soup is a Python library for pulling data out of HTML and XML files. It works with your favorite parser to provide idiomatic ways of navigating, searching, and modifying the parse tree. It commonly saves programmers hours or days of work.

These instructions illustrate all major features of Beautiful Soup 4, with examples. I show you what the library is good for, how it works, how to use it, how to make it do what you want, and what to do when it violates your expectations.

The examples in this documentation should work the same way in Python 2.7 and Python 3.2.

You might be looking for the documentation for Beautiful Soup 3. If so, you should know that Beautiful Soup 3 is no longer being developed, and that Beautiful Soup 4 is recommended for all new projects. If you want to learn about the differences between Beautiful Soup 3 and Beautiful Soup 4, see Porting code to BS4.







