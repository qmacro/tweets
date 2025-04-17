# @qmacro tweet archive

I now have a GitHub Pages hosted searchable and browsable archive of my tweets, thanks to Darius Kazemi and Simon Willison. It's at <https://qmacro.org/tweets/> and the source is this repository.

I used Darius's [Twitter Archiver](https://github.com/dariusk/twitter-archiver) tool to convert my tweet archive (that I'd [downloaded](https://x.com/settings/download_your_data) at the end of 2024), and then Simon's minimal YAML configuration example for [building and deploying a custom site using GitHub Actions and GitHub Pages](https://til.simonwillison.net/github-actions/github-pages).

Because I've already got a domain set up and linked to the GitHub Pages hosting mechanism, I can use this repo's pages hosting at <https://qmacro.org/tweets/> as well as my main website which is also made available via the pages hosting for [my main website and blog repo](https://github.com/qmacro/qmacro.github.io) at <https://qmacro.org/>.

I cloned the Twitter Archiver's repo and hosted the resources locally, so I could tweak the style and text slightly to my liking. It's all editable within the [app.js](https://github.com/dariusk/twitter-archiver/blob/master/app.js) file. In case you don't want or need to tweak anything, you can use [the instance hosted by Darius](https://tinysubversions.com/twitter-archive/make-your-own/) - note that your archive does NOT get uploaded to the website, it's just processed (and the new hostable archive created) by JavaScript in your own browser.
