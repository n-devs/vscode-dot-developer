# Dot Developer 

[![Version](https://vsmarketplacebadge.apphb.com/version/n-devs.vscode-dot-developer.svg)](https://marketplace.visualstudio.com/items?itemName=n-devs.vscode-dot-developer)
[![Install](https://vsmarketplacebadge.apphb.com/installs/n-devs.vscode-dot-developer.svg)](https://marketplace.visualstudio.com/items?itemName=n-devs.vscode-dot-developer)
[![Rating(Star)](https://vsmarketplacebadge.apphb.com/rating-star/n-devs.vscode-dot-developer.svg)](https://marketplace.visualstudio.com/items?itemName=n-devs.vscode-dot-developer)

A Visual Studio Code theme for the Dot Developers out there. Fine-tuned for those of us who like to code late into the night. Color choices have taken into consideration what is accessible to people with colorblindness and in low-light circumstances. Decisions were also based on meaningful contrast for reading comprehension and for optimal razzle dazzle. ✨

As of 1.0.0, there's a Light Owl Theme too! Color balanced from the Dark version for easy viewing in daylight. 🌅

About this theme, and some of the considerations made while creating it (as well as _how_ to create it should you want to make your own): [https://css-tricks.com/creating-a-vs-code-theme/](https://css-tricks.com/creating-a-vs-code-theme/)

## Dot Developer
![First Screen](first-screen.jpg)
![Dot Developer Frameworks](three-dark.jpg)

# Installation

1.  Install [Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=n-devs.vscode-dot-developer)
2.  Launch Visual Studio Code
3.  Choose **Extensions** from menu
4.  Search for `Dot Developer`
5.  Click **Install** to install it
6.  Click **Reload** to reload the Code
7.  From the menu bar click: Code > Preferences > Color Theme > **Dot Developer**

## Disable Italics

If you wish to disable italics, there is now a no-italic theme available. You will have access to both, select **Dot Developer No Italics** as your color theme.

## Other versions

The community is awesome and has ported this theme over to other environments.

#### Theme

- VSCode: [https://github.com/n-devs/vscode-dot-developer](https://github.com/n-devs/vscode-dot-developer)

## Separate the Editor from the Sidebar

This theme uses contrast sparingly so that when it's applied, it's more meaningful. This can help reduce noise and improve your ability to scan. However, some of the decisions may not work for everyone. One such decision that some disagree on is whether or not to have a separation between the editor and sidebar, and the amount of contrast. If you wish for this to have more visual signifigance, please paste this into your user settings preferences. These are my recommendations for these settings but you can use whatever colors you wish. ☺️

```
"workbench.colorCustomizations": {
  "[Dot Developer]": {
    "activityBar.background": "#000C1D",
    "activityBar.border": "#102a44",
    "sideBar.background": "#001122",
    "sideBar.border": "#102a44",
    "sideBar.foreground": "#8BADC1"
  },
  "[Dot Developer (No Italics)]": {
    "activityBar.background": "#000C1D",
    "activityBar.border": "#102a44",
    "sideBar.background": "#001122",
    "sideBar.border": "#102a44",
    "sideBar.foreground": "#8BADC1"
  }
},
```

## Preferences shown in the preview

The font in the preview image is Dank Mono, [available here](https://dank.sh/). Editor settings to activate font ligatures:

```
"editor.fontFamily": "Dank Mono",
"editor.fontLigatures": true,
```

The preview image is using [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer), a really cool extension that highlights matching brackets. This can help reduce unwanted errors.

I use this setting:

```
"bracketPairColorizer.forceIterationColorCycle": true,
```


## Misc

This is my first foray into creating a theme, so if you see something amiss, please feel free to [file an issue](https://github.com/sdras/night-owl-vscode-theme/issues)! I'm sure there are things I missed.

Any relevant changes for each version are documented in the changelog. Please update and check the changelog before filing any issues, as they may have already been taken care of.

This palette was inspired in part by Material Palenight [Theme](https://marketplace.visualstudio.com/items?itemName=whizkydee.material-palenight-theme), and the accessibility idea was inspired in part by Solarized [Themes](http://ethanschoonover.com/solarized)
