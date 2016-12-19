# Slack Night Mode
A Stylish style for easy Slack theming. [CC0](http://creativecommons.org/publicdomain/zero/1.0/).

Forked from [laCour/slack-night-mode](https://github.com/laCour/slack-night-mode). Thanks for your excellent work, Jonathan.

The differences are that my edits use the custom font, when set, for input fields in addition to text display.
I also added my preferred theme variants.

## Usage

This theme requires that you use the Stylish extension for your browser (available for [Firefox](https://addons.mozilla.org/en-US/firefox/addon/stylish/), [Chrome](https://chrome.google.com/webstore/detail/stylish/fjnbnpbmkenffdnngjfgmeleoegfcffe), and [Safari](http://sobolev.us/stylish/)).

Further usage instructions may be found at the original project. You can search for my variants on userstyles.org.

![Black Screenshot](https://userstyles.org/style_screenshots/117475_after.png)

All themes can be built by running `make` (you will need [SassC](http://sass-lang.com/libsass)).

## Theme Variants

### Aubergine

![Aubergine Screenshot](https://userstyles.org/style_screenshots/101971_after.png)

### Tomorrow Dark ([source](scss/themes/_tomorrow_dark.scss) - [build](css/variants/tomorrow_dark.css))

Themed to be similar to the base palette of [base16-tomorrow-dark](https://github.com/chriskempson/base16) by Chris Kempson.

![screenshot](screenshots/screenshot.png)

* **Arc ([source](scss/themes/_arc-dark.scss) - [build](css/variants/arc-dark.css))** _by [@Lemmmy](https://github.com/Lemmmy)_
* **Midnight Blue ([source](scss/themes/_midnight-blue.scss) - [build](css/variants/midnight-blue.css))** _by [@matt-h](https://github.com/matt-h)_
* **Tomorrow Dark (base16) ([repository](https://github.com/danarnold/slack-night-mode))** _by [@danarnold](https://github.com/danarnold)_

### Tomorrow Dark Monospaced ([source](scss/themes/_tomorrow_dark-monospaced.scss) - [build](css/variants/tomorrow_dark-monospaced.css))

Uses monospaced font families.

### Tomorrow Dark Monospaced Input ([source](scss/themes/_tomorrow_dark-monospaced-input.scss) - [build](css/variants/tomorrow_dark-monospaced-input.css))

This one uses Input Sans Narrow as the font, and falls back to the standard monospaced options if it isn't available.

![screenshot](screenshots/screenshot-input.png)
