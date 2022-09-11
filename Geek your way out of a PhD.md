# Geek your way out of a Ph.D.

This page collects a set of digital tools, websites, and tutorials that I found. I think that some of the tools in this list might be considered essential and others might be simply 'useful to know they exist' for both Ph.D. students and researchers in general. 

I find it very hard to discover tools and websites of this type. I discovered most of those tools by chance wandering on the internet. Some other tools instead, were discovered because of a specific need I had as a Ph.D. student (hence the name of the list). I think that the best way to discover new tools and methods for doing research is by talking to colleagues and friends, but a collection to look at when in need, might be of help. 

There is no affiliation with any of the links on this page. The sole purpose of this collection is to spread knowledge on tools that might be useful for research but one might not have encountered yet. My hope is that anyone can contribute to this list and allow others to discover new interesting websites, digital tools or even tutorials that might help advance research.

Most of the tools presented here are free or even open source, for ease of accessibility.

This list is by no means complete, there are many tools that I do not know of or I have simply not encountered yet. If you know some tool or website that you think might be useful to others, please update this list on GitHub or simply let me know what those are. 

## Literature overview

Given a paper, it is not always simple to discover what research it is based on, or what has been done after that. Of course, looking at the references of the paper and what papers cite your original paper (on Google Scholar for example) does the job but a graphical interface with useful commands and filters might help. 
In this section, there are a few websites that help you search through papers and authors to get an idea of the context of a given paper. Some of the websites look at the citations (e.g. Citation Gecko) others look at different similarity metrics (e.g. Connected Papers).

### [Connected Papers](https://www.connectedpapers.com/)
<img src='https://www.connectedpapers.com/share-preview-img.png' width=50%/>

### [Citation Gecko](https://citationgecko.azurewebsites.net/)
<img src='https://miro.medium.com/max/1400/1*-duUauzb1Ha3SLQzbFlApQ.png'/>

### [Research Rabbit](https://researchrabbitapp.com/home)
<img src='https://miro.medium.com/max/1089/1*COz33oKcdgsEmMh1H9GI1w.png'/>

### [Inciteful](https://inciteful.xyz/)
<img src='http://library.hkust.edu.hk/sc/wp-content/uploads/sites/5/2021/04/Inciteful-screen-cap-1.png'/>

### [Web of science](https://www.webofscience.com/wos/woscc/basic-search)

### [Scimago](https://www.scimagojr.com/)

### [Scopus](https://www.scopus.com/search/form.uri?display=basic#basic)

## Keeping up with new research in your field

It is no secret that keeping up with current research is not simple. Here we have a digital tool that sends you an email weekly on some of the new publications in your field.

### [Google Scholar Alerts](https://scholar.google.com/intl/it/scholar/help.html#alerts)

### [Arxiv recent submissions](https://arxiv.org/)

## Literature Organization

Of all the sections in this list, I think this is the most important one. I find that having a digital tool that keeps the hundreds of papers you have laying around on your computer organized for you is a must. 

### [Zotero](https://www.zotero.org/)
<img src='https://upload.wikimedia.org/wikipedia/commons/8/89/Zotero-5-macOS-Screenshot%402x.png'/>

### [Mendeley](https://www.mendeley.com/)
<img src='https://static.mendeley.com/md-stitch/releases/live/stable_release_desktop_latest_mrm_img.55a28946.png'/>

## Latex IDE

This section contains a bunch of programs to compile documents in latex. Each program has its pros and cons, none is perfect. However, if you are not happy with your current Latex setup, it is good to know that there are other options. 

### [Overleaf](https://it.overleaf.com/)

### [VSCode](https://code.visualstudio.com/) + [Latex workspace](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)

### [TexStudio](https://www.texstudio.org/)

## Version control

This list is for sure very well known to programmers but I think it is important for anyone who has to work with digital files. The problem that is solved by the programs and websites in this list, is the one of keeping track of the different versions of files and projects. This is usually used for software development but it can be used also for latex articles (Overleaf uses it internally) or any type of digital file you can imagine. If you ever found yourself naming your files "artile.tex", "artile_2.tex", "artile_3.tex", "artile_3_1.tex", "artile_3_updated.tex" and you are tired of this method, this list is for you.

### [Git](https://git-scm.com/)

### [GitHub](https://github.com/)

### [GitLab](https://about.gitlab.com/) 

## Spell Checkers

If you want to be sure to avoid grammatical errors, there are options for that. Be careful though, they are not perfect, you should check every correction they want to make. 

### [Grammarly](https://app.grammarly.com/)

### [Writefull](https://www.writefull.com/)

## Note taking

In recent years, a large number of note-taking apps have surfaced. Each app is different, having its own philosophy, but there might be something for your taste.

### [Obsidian](https://obsidian.md/)
<img src='https://obsidian.md/images/screenshot.png'/>
Guides on how to use Obsidian for academic work can be found [Here](https://betterhumans.pub/how-to-boost-your-productivity-for-scientific-research-using-obsidian-fe85c98c63c8) and [Here](https://betterhumans.pub/obsidian-tutorial-for-academic-writing-87b038060522).

### [Notion](https://www.notion.so/)

### [Evernote](https://evernote.com/intl/it)

### [Xournal ++](https://xournalpp.github.io/)
This is an amazing open-source app for note-taking and PDF annotation on computers (with any operative system) and a touchscreen or Wacom tablet.

### [Goodnotes](https://www.goodnotes.com/)
Unfortunately, this works only on iPad.

## Graphs and figures for papers

I find this section the most disappointing of all. If you write papers in LaTex you know that TikZ allows you to produce amazing graphs and drawings with the same style as your paper (because it uses the same rendering engines). However, writing code for TikZ is not trivial at all, and it is for sure time-consuming. Unfortunately, the is no good solution to draw figures in a graphic environment and then export them in TikZ. Every solution I tried works only partially or with some caveats. Also, many programs to produce beautiful figures are (very) expensive (e.g. Adobe Illustrator).  Here you can find the list of the best tools I found.   

### [Inkscape](https://inkscape.org/it/)
Inkscape is an open-source program for vector graphic design. In my opinion, this is the best solution available at the moment.  
The two tutorials by [Gilles Castel](https://castel.dev/post/lecture-notes-2/) and [Pingbang Hu](https://www.pbb.wtf/posts/VSCode-LaTeX-Inkscape) show how to use Inkscape to produce figures in PDF with separate text that is then rendered by LaTex. The results, as it is shown in the two tutorials, are amazing. 

There is also an [extension](https://code.google.com/archive/p/inkscape2tikz/) for Inkscape that allows exporting the figure in TikZ.  

The only major problem with this solution is that Inkscape is not easy to use.

### [Quiver](https://q.uiver.app/)
Quiver is a lovely website to draw commutative diagrams in Tikz. It is extremely simple to use but it only allows for commutative diagrams. 

### [LaTeXDraw](http://latexdraw.sourceforge.net/)

### [TikZiT](https://tikzit.github.io/)

## Presentations

Nothing wrong with power point or google slides, it is simply good to know that there are alternatives.

### [Beamer](https://it.overleaf.com/learn/latex/Beamer)
It is the LaTex environment dedicated to presentations. It is very fast to produce a presentation if you need to use a lot of formulae from one of your papers written in latex. 

### [Manim](https://github.com/ManimCommunity/manim)
Manim is a python library developed by a Youtuber (3Blue1Brown) for the sole purpose of mathematical animations. The results are stunning.

### [reveal.js](https://revealjs.com/)

## Self promotion

Having an online presence might be important in some cases. Here are few tools to know.

### [GitHub Pages](https://pages.github.com/)
If you want to have a personal website where to show your research, you can host it (for free!!) on GitHub. For a basic website you do not even know how to build a website! You just need a [markdown](https://www.markdownguide.org/) file.

### [Google Scholar Profiles](https://scholar.google.com/intl/it/scholar/citations.html)

## Funds, Grants and Fellowships

A couple of websites to have a look when preparing for your next position as a researcher.

### [EURAXESS](https://euraxess.ec.europa.eu/)

### [Vacancy.edu](https://vacancyedu.com/)
