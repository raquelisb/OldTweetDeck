# OldTweetDeck
Returns old TweetDeck, for free!
Currently no easy way to install, but you can download this repo and load it as unpacked extension in Chrome/Edge/Opera/any Chromium browser.  
  
If you're interested in getting 2015 Twitter back, you can also check out [OldTwitter](https://github.com/dimdenGD/OldTwitter) extension.  
  
![Screenshot](https://lune.dimden.dev/9713d947d56.png)  

### Other languages
[한국어 README](docs/README_KO.md)
## Installation
### Chromium (Chrome, Edge, Opera, Brave, Etc) 
1. Go to [Release page](https://github.com/dimdenGD/OldTweetDeck/releases) and download `OldTweetDeckChrome.zip`
2. Unzip the archive
3. Go to extentions page(``chrome://extensions``)
4. Enable developer mode (there should be switch somewhere on that page)
5. Press "Load unpacked" button
6. Select folder with unzipped archive 
7. Go to tweetdeck.twitter.com and enjoy old TweetDeck
8. [Donate to encourage continued support](https://www.patreon.com/dimdendev)

### Firefox
#### Nightly / Developer Edition
1. Go to [Release page](https://github.com/dimdenGD/OldTweetDeck/releases) and download `OldTweetDeckFirefox.zip`
2. Go to Firefox Configuration Editor (`about:config`)
3. Change the preference `xpinstall.signatures.required` to false
4. Go to addons page(``about:addons``)
5. Press "Install Add-on From File..." button
6. Select zip file you downloaded
7. Go to tweetdeck.twitter.com and enjoy old TweetDeck
8. [Donate to encourage continued support](https://www.patreon.com/dimdendev)

#### Stable
**I recommend using the Nightly version.** Here's non-recommended way for Stable version.
1. Go to `about:debugging#/runtime/this-firefox`
2. Press "Load Temporary Add-on" and select zip file you downloaded

**Installing this way on Firefox will remove it after closing browser.**

### Safari
NOT SUPPORT

## Update
Remove extension and reinstall. This is the most reliable way to update.
This extension does not save sensitive settings in local.

## Better TweetDeck
I've made a fork of BetterTD that works with this extension, you can find it [here](https://github.com/dimdenGD/BetterTweetDeck/). Install it the same way as this extension, except get archive from [Releases](https://github.com/dimdenGD/BetterTweetDeck/releases) page instead of "Code" button.  
 
## FAQ
#### There is warning; Manifest version 2 is deprecated, and support will be removed in 2023.
Ignore this warning.
 
## ~~Transparent disclaimer~~
Old info that was here is now outdated.  
I've remade extension into manifest v2. Now all files are included in extension itself, no external server required!