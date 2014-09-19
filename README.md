#MarKit

An Objective-C Markdown parser. MarKit can parse [John Gruber's Markdown](http://daringfireball.net/projects/markdown/) in real time. Rather than directly converting Markdown into HTML, MarKit converts the text into a series of tokens which can then be used to produce an `NSAttributedString` or HTML.

**Coming soon..***

##Features

* Full support for all of the Markdown features described by John Gruber (N.B. this doesn't necessarily fully support [Common Mark](http://commonmark.org/))
* Exports HTML, `NSAttributedString` and plain text
* Can run synchronously with `NSTextStorage` so that you can get *customizable* Markdown formatting in real time (a little like TextMate) 
* Really, reall fast
* Apache licensed

##Coming soon

* The code needs a decent amount of tidying up still
* Swift compatibility
* [Knyt](https://github.com/programmingthomas/Knyt) compatibility
