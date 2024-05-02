# Chrome ウェブストア経由の拡張機能

- [Chrome ウェブストア](https://chromewebstore.google.com/)

## Install

1. Access each URL in `~/dotfiles/chromewebstore/extensions` with Google Chrome.
2. Click "Add Chrome" button.
3. If you want to output the current extensions, execute `ls -l ${HOME}/Library/Application\ Support/Google/Chrome/Default/Extensions | awk '{print \$9}' | sed 's/^/https:\/\/chrome.google.com\/webstore\/detail\//g' | sed -e '1,2d' > ~/dotfiles/chrome/extensions`.