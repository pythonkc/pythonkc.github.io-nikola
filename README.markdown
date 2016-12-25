# `pythonkc.github.io-nikola`

This is an attempt to generate `pythonkc.github.io` using [Nikola](https://getnikola.com).

## How to use

* Clone this repository to your local computer.
* Create a virtual environment. I recommend using Python 3.6.x, as that is the version I used.
* Activate the virtual environment and install the requirements: `pip install -r requirements.txt`
* Run `nikola build` to generate the site.
* Run `nikola server --browser` to open locally generated site in your default browser.

## Why?

After working with Julie Stark, we discovered [Pelican](http://blog.getpelican.com) on Microsoft Windows was problematic at best. Reading the Nikola documentation suggested it has better support for Microsoft Windows. We'll see.

## Caveat Emptor!

Currently, this site generates using the default Nikola theme, which is built upon [Mako](http://www.makotemplates.org) templates. The only customization I've done is to make posts and pages written in Markdown (named `*.markdown`) be detected and processed by Nikola. For some reason, _pages_ (as opposed to _posts_) do not appear on the generated site. I'm absolutely certain this is completely my fault and a closer reading of the documentation will illuminate the error of my ways.
