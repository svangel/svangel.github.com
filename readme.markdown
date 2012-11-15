# SV Angel Website User Guide

# How To

## Compile Sass to CSS

Assuming you already have compass installed. If you don't, type:

	$ gem install compass
	
Then you can compile the css with this command

    $ compass watch

## Build blog

    $ jekyll --pygments --safe

## View site

    $ cd _site
    $ python -m SimpleHTTPServer

or

To install jekyll for the firs time

	$ gem install jekyll
	
To start the webserver to view the site.

    $ jekyll --pygments --safe --server --auto

# Resources

* Jekyll
  * [github](https://github.com/mojombo/jekyll)
  * [wiki](https://github.com/mojombo/jekyll/wiki)
    * [template data](https://github.com/mojombo/jekyll/wiki/template-data)
    * [config](https://github.com/mojombo/jekyll/wiki/Configuration)
* Liquid
  * [For Designers](https://github.com/shopify/liquid/wiki/liquid-for-designers)
  * [For Programmers](https://github.com/Shopify/liquid/wiki/Liquid-for-Programmers)
