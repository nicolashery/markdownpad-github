# GitHub stylesheet for MarkdownPad

Like a lot of developers I imagine, I've become used to seeing [Markdown](http://daringfireball.net/projects/markdown/) render in [GitHub](https://github.com/) for documentation and README files.

On a Windows computer, I use the very nice (and free!) [MarkdownPad](http://markdownpad.com) by [Evan Wondrasek](http://evanw.com/). Not having found any other way/application that will allow me to preview my Markdown documents as close as possible to how they would look on GitHub, I put together this stylesheet. Maybe someone else will find it useful.

## Installation

In MarkdownPad just got to **Tools > Options > HTML/CSS**, check **Use custom stylesheet** and paste in the content of [markdownpad-github.css](/nicolahery/markdownpad-github/blob/master/markdownpad-github.css) (erasing what was already in the textbox).

## Limitations

This is just a stylesheet, so the special functions and syntax highlighting of [GitHub Flavored Markdown](http://github.github.com/github-flavored-markdown/) will *not* work (they would need to be integrated in the MarkdownPad application itself, maybe one day?).

For instance, writing this fenced code block in your Markdown document:

    ```python
    def hello:
        print 'Hello World!'
    ```

Will not produce the desired result with syntax highlighting in MarkdownPad (but obviously will look fine once on GitHub).