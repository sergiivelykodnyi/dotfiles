# Sergii Velykodnyi's Dotfiles

## Install

In the beginning, you need to check installation the git, zsh in your system.
  * For check zsh see this doc [Installing-ZSH](https://github.com/robbyrussell/oh-my-zsh/wiki/Installing-ZSH)
  * For check git run this `git --version` if you don't see message like this `git version 2.17.0` you need to install git. For masOS you can run `brew install git`, for Ubuntu `sudo apt install git`.

### Clone repository

```bash
$ git clone https://github.com/sergiivelykodnyi/dotfiles.git
$ cd dotfiles
```

### Install zsh config
if
```bash
$ sh install-zsh.sh
```

### Install bash config

```bash
$ sh install.sh
```

### Add user data for Git

Open the file `~/.gituser` and add your data:
```
[user]
  name = enter your name
  email = enter your email
```

## Colors
```
txtblk='\e[0;30m' # Black - Regular
txtred='\e[0;31m' # Red
txtgrn='\e[0;32m' # Green
txtylw='\e[0;33m' # Yellow
txtblu='\e[0;34m' # Blue
txtpur='\e[0;35m' # Purple
txtcyn='\e[0;36m' # Cyan
txtwht='\e[0;37m' # White
bldblk='\e[1;30m' # Black - Bold
bldred='\e[1;31m' # Red
bldgrn='\e[1;32m' # Green
bldylw='\e[1;33m' # Yellow
bldblu='\e[1;34m' # Blue
bldpur='\e[1;35m' # Purple
bldcyn='\e[1;36m' # Cyan
bldwht='\e[1;37m' # White
unkblk='\e[4;30m' # Black - Underline
undred='\e[4;31m' # Red
undgrn='\e[4;32m' # Green
undylw='\e[4;33m' # Yellow
undblu='\e[4;34m' # Blue
undpur='\e[4;35m' # Purple
undcyn='\e[4;36m' # Cyan
undwht='\e[4;37m' # White
bakblk='\e[40m'   # Black - Background
bakred='\e[41m'   # Red
bakgrn='\e[42m'   # Green
bakylw='\e[43m'   # Yellow
bakblu='\e[44m'   # Blue
bakpur='\e[45m'   # Purple
bakcyn='\e[46m'   # Cyan
bakwht='\e[47m'   # White
txtrst='\e[0m'    # Text Reset
```


## Thank you for resources
* [Github dotfiles](https://dotfiles.github.io/)
* [Mathias’s dotfiles](https://github.com/mathiasbynens/dotfiles)
* [Managing Your Dotfiles](http://www.anishathalye.com/2014/08/03/managing-your-dotfiles/)

## License

The code is available under the [MIT license](LICENSE).
