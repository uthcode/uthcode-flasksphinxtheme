uthcode-flasksphinxtheme
========================

uthcode flask sphinx theme

This has some specific settings with respect to Uthcode project. Like custom theme, uthcode logo, uthcode favicon, disqus comments and google analytics.

How to use
----------

    git submodule add git@github.com:uthcode/uthcode-flasksphinxtheme.git _themes

And in the conf.py of sphinx documentation, have this snippet.

   sys.path.append(os.path.abspath('_themes'))
   html_theme_path = ['_themes']
   html_theme = 'flask'

