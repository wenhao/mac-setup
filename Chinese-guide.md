##Mac设置指南

###系统设置
####功能键

`系统偏好设置->键盘`，勾选`将F1／F2等键用作标准功能键`

####全键盘控制

`系统偏好设置->键盘->快捷键`，勾选`所有控制`

####Spotlight快捷键

`系统偏好设置->键盘->快捷键->Spotlight->显示Spotlight搜索`，设置快捷键`⌘空格`

####Trackpad轻点来点按

`系统偏好设置->触控板－>光标与点按`，勾选`轻点来点按`

####Dock

`系统偏好设置->Dock->置于屏幕上的位置`，建议放在左边或者右边

####更改`Caps Lock`键为`Control`键

`系统偏好设置->键盘->修饰键`，将`Caps Lock`键改为`^Control`

####触发角

`系统偏好设置->桌面与屏幕保护程序->触发角`，将右下角设置为`将显示器置入睡眠状态`

###工具与软件

####[Homebrew]

安装Homebrew

```shell
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

安装常用的开发工具

```shell
brew install mysql gradle maven node
```
####[Homebrew Cask]

安装常用的软件

```shell
brew cask install google-chrome intellij-idea macdown atom
```

####[jenv]

```shell
brew  install jenv
```
把下面内容加入到.zshrc文件内

if which jenv > /dev/null; then eval "$(jenv init -)"; fi

export JENV_ROOT=/usr/local/opt/jenv

```shell
jenv add <jdk home path>
```

####[Oh My Zsh]

```shell
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

plugins=(git z)

ZSH_THEME="agnosterzak"

source ~/.zshenv

####Moom调节窗口大小

```shell
brew cask install moom
```

####CheatSheet显示快捷键

```shell
brew cask install cheatsheet
```

####[Atom]编辑器

```shell
brew cask install atom
```

###[MacDown]

```shell
brew cask instll macdown
```

####[Vimium]

Google Chrome Vimium插件

####[Manico]切换应用

```shell
brew cask install manico
```

####[Shortcat]快捷访问

```shell
brew cask install shortcat
```


[Homebrew]: http://brew.sh/
[Homebrew Cask]: http://caskroom.io/
[jenv]: http://www.jenv.be/
[Oh My Zsh]: http://ohmyz.sh/
[Vimium]: https://vimium.github.io/
[MacDown]: https://github.com/MacDownApp/macdown
[Atom]: https://github.com/atom/atom
[Manico]: https://manico.im/
[Shortcat]: https://shortcatapp.com/
