# What dis?

Here you'll find my dotfiles and my setup preferences. All nice and neat. It's a work in progress, mostly.

**Important:** if for some reason you see fit to try some of these things out, please fork the repo and remove things you don't want or need before using them. Don’t blindly use my settings unless you know what that entails.

# Installation

### First things first
- Take a moment and appreciate what an unadulterated, fresh mac looks like. Yeah, it's pretty neat. Let's get to the nitty-gritty.
- Sign in to Apple accounts; set System Preferences; set preferred backgrounds!
- Download and install the important stuff:
    - [Alfred](www.alfredapp.com)
    - [Dash](https://kapeli.com/dash)
    - [iTerm 2](https://www.iterm2.com/downloads.html) - set up hotkey shortcut Cmd-Ctrl-T
    - [Karabiner](https://pqrs.org/osx/karabiner/)
- Download from App Store
    - Xcode
      - Once installed, open to install tools!
    - 1Password (also get safari/crome extension)
    - Magnet (and set hotkeys)

### Let's get Phys... no. Let's get automated!
- In iTerm `git clone https://github.com/rouxbuciu/.dotfiles.git` in the home directory
- Then `cd .dotfiles` & `bootstrap.exclude.sh` & grab some hangtime because this'll take a while.

### XVim - why settle for less!?
- Rename standard xcode to Xcode-Distribution (if you need a distribution Xcode)
- Download another version of Xcode [from Apple](https://developer.apple.com/download/more/)
- Sign your own [code signing certificate](https://github.com/XVimProject/XVim2/blob/master/SIGNING_Xcode.md)
- Install [XVim2](https://github.com/XVimProject/XVim2)
- If .xvimrc doesn't exist, create it
    - `curl https://raw.githubusercontent.com/rouxbuciu/toolPreferences/master/xvimrc > .xvimrc`
- Go to ~Library/Developer/Xcode/UserData/Keybindings
    - Symlink my personal bindings `ln -sv ~/.dotfiles/RouxAlternateBindings.idekeybindings ~/Library/Developer/Xcode/UserData/Keybindings/`

### Spacemacs
- Spacemacs install instructions: https://github.com/syl20bnr/spacemacs (Install dev branch (if stable))

### Other
- In chrome, don't forget to install `vimium`
- In Alfred, set up various workflows or shortcuts you need.

# Why a dotfiles repo?

Inspired by [mathiasbyens'](https://github.com/mathiasbynens/dotfiles), the dotfile repo is a great way to keep all your preferences the same across all dev environments! Tasty! furthermore.... it helps get a system going faster!

# Why share?
Sharing is caring. We learn from each other 🌷

# License

The contents of this repo are licensed under the MIT license.

# Contributing

If you have any ideas or suggestions, feel free to open up an issue or shoot through a pull request! Thanks!

Feel free to fork whenever you want!
