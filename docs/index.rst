:tocdepth: 2

=====================
Building with Tarbell
=====================

This tutorial will walk you through the process of building a simple
news application and publishing it on the web. You will learn the basics
of responsive design and charting with D3 by visualizing data by the
`@chitowncoders <http://twitter.com/chitowncoders/>`_ `Cook
County Jail scraper <https://github.com/sc3/cookcountyjail/>`_.

You will get hands-on experience in every stage of the development process:
working with data, sketching mockups, writing HTML, CSS, and Javascript
and recording your work using Git's version control system. 

You will learn to use Backbone JS to structure your application, Underscore JS
to process data, Twitter Bootstrap to structure your markup, and D3 for 
data visualization. The techniques used here were first described in
`Responsive Charts with D3 and Backbone 
<http://blog.apps.chicagotribune.com/2014/03/07/responsive-charts-with-d3-and-backbone/>`_
by Ryan Nagle.

This guide was prepared for Migrahack Mexico City, April 3-6, 2014 and presented
by `David Eads <http://twitter.com/eads>`_.

* Code repository: `https://github.com/sc3/26thycalifornia <https://github.com/sc3/26thycalifornia>`_
* Demonstration: `http://26thycalifornia.recoveredfactory.net <http://26thycalifornia.recoveredfactory.net>`_
* Documentation: `http://migrahack.readthedocs.org/ <http://migrahack.readthedocs.org/>`_
* Issues: `https://github.com/sc3/26thycalifornia/issues <https://github.com/sc3/26thycalifornia/issues>`_

Prerequisites
=============

1. A modern web browser (Chrome or Chromium)
2. A `text editor <https://en.wikipedia.org/wiki/Text_editor>`_ to work with plain text files
3. A `command-line interface <https://en.wikipedia.org/wiki/Command-line_interface>`_ to interact with your computer
4. `Git <http://git-scm.com/>`_ version control software
5. (Optional) An account at `GitHub.com <http://www.github.com>`_


Web browser
-----------

Firefox or Chrome. 


Text editor
---------------------

You'll be editing simple `"plain text" files <https://en.wikipedia.org/wiki/Text_file>`_.

Just like you need a word processor for writing human language, you need a text editor
for working with plain text such as HTML markup, CSS, and Javascript.

`Sublime Text <http://www.sublimetext.com/3>`_ is highly recommended. It's fast,
simple, and runs on all major platforms.


Command-line interface
----------------------

Every computer should be a way to open a window that lets you type in commands. Different operating
systems give this tool slightly different names, but they all have some form of it, and there are
alternative programs you can install as well. 

On Windows you can find the command-line interface by opening the "command prompt." Here are instructions for 
`Windows 8 <http://windows.microsoft.com/en-us/windows/command-prompt-faq#1TC=windows-8>`_ 
and `earlier versions <http://windows.microsoft.com/en-us/windows-vista/open-a-command-prompt-window>`_.

On Apple computers, you open the `"Terminal" application 
<http://blog.teamtreehouse.com/introduction-to-the-mac-os-x-command-line>`_. 

Ubuntu Linux comes with a program of the `same name 
<http://askubuntu.com/questions/38162/what-is-a-terminal-and-how-do-i-open-and-use-it>`_.


Git and GitHub
--------------

`Git <http://git-scm.com/>`_ is a version control program for saving the changes 
you make to files over time. This is useful when you're working on your own, 
but quickly becomes essential with large software projects, especially if you work with other developers. 

`GitHub <https://github.com/>`_ is a website that hosts git code repositories, both public and private. It comes
with many helpful tools for reviewing code and managing projects. It also has some 
`extra tricks <http://pages.github.com/>`_ that make it easy to publish web pages, which we will use later. 

GitHub offers helpful guides for installing Git in 
`Windows <https://help.github.com/articles/set-up-git#platform-windows>`_,
`Macs <https://help.github.com/articles/set-up-git#platform-mac>`_ and
`Linux <https://help.github.com/articles/set-up-git#platform-linux>`_. You can verify
it's installed from your command line like so:

.. code-block:: bash

    # You don't have to type the "$" It's just a generic symbol 
    # geeks use to show they're working on the command line.
    $ git --version

Once that's done, you should create an account at GitHub, if you don't already have one.
It shouldn't cost you anything. `The free plan <https://github.com/pricing>`_ 
is all that's required to complete this lesson.



Planning: Know your data
========================

- Acquire meaningful data (the data for this tutorial comes from a 
  `scraper <https://github.com/sc3/cookcountyjail>`_).
- Question the data:
  - Does the data need cleaning or scrubbing?
  - What comparisons can be made?
  - How can the data be bucketed or categorized?
  - How can the data be normalized and averaged?
- Process data: "Boil down" into useful summary data structures.
  - Time series
  - Ratios
  - Distributions 
- Publish raw and summarized data with a web API

`Time summaries of crime incident data <https://www.dropbox.com/s/m3jlrrld5rnmnpw/time%20summaries%20of%20crime%20incident%20data%20-%20data%20made%20simple%20hackathon%202014.pdf>`_ by David Eads describes how the the Chicago Tribune applies these techniques to crime data.


Planning: Sketch your interface
===============================

Todo (need photos of sketches)


Set up: Bootstrap your project
==============================

.. note::

    Don't care about the nitty gritty details of setting up your project?
    Not running OS X or Linux? Just skip ahead to the next chapter. 


Project setup details


Build: Make a time-series bar chart 
===================================


Build: Summarize data with collection object methods
====================================================


Build: Writing words with data
==============================


Build: Adding chart interaction
===============================







