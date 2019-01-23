# Slack Theme CLI

A Command-Line Tool for changing Slack's desktop app colors, like

## Night Mode

![image](https://user-images.githubusercontent.com/11996508/48413960-98fac400-e749-11e8-8151-327c6d60f6d0.png)

## Midnight-Blue Mode

![image](https://user-images.githubusercontent.com/11996508/48414135-19b9c000-e74a-11e8-8aea-7dd7df8dd885.png)

## Aubergine Mode

![image](https://user-images.githubusercontent.com/11996508/48414177-3ce46f80-e74a-11e8-98fb-2f0ce5d0a5f9.png)

## How to install

To download and install, run the following code in your terminal:

```sh
curl https://raw.githubusercontent.com/mykeels/slack-theme-cli/master/slack-theme -O && sh slack-theme install && . ~/.bash_profile
```

### For Zsh users

If you use zsh as your shell environment, you might want to run this instead:

```sh
curl https://raw.githubusercontent.com/mykeels/slack-theme-cli/master/slack-theme -O && SLACK_THEME_SHELL_PROFILE=~/.zshenv sh slack-theme install && . ~/.zshenv
```

## How to use

See command break-down below:

```txt
SYNOPSIS
     slack-theme
     slack-theme day
     slack-theme night
     slack-theme night-mono
     slack-theme aubergine
     slack-theme aubergine-mono
     slack-theme arc-dark
     slack-theme midnight-blue
     slack-theme midnight-blue-mono
     slack-theme solarized-dark
     slack-theme solarized-light
     slack-theme install
     slack-theme uninstall

COMMANDS
     day
          Revert to Day Mode

     night
          Use Black CSS

     night-mono
          Use Night-Mono CSS

     aubergine
          Use Aubergine CSS

     aubergine-mono
          Use Aubergine-Mono CSS

     arc-dark
          Use Arc-Dark CSS

     midnight-blue
          Use Midnight-Blue CSS

     midnight-blue-mono
          Use Midnight-Blue-Mono CSS

     solarized-dark
          Use Solarized-Dark CSS

     solarized-light
          Use Solarized-Light CSS
```

## Credits 😍

Huge thanks to:

- [Slack Night Mode](https://github.com/laCour/slack-night-mode)
- [Easy Dark Mode for Slack](https://dev.to/changoman/easy-dark-mode-for-slack-1mmn)