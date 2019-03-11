# linux-setup
My preferred stuff to customize linux's experience

## Gnome Tweaks
```bash
sudo dnf install gnome-tweaks
```

## [Gnome Materia Theme](https://github.com/nana-4/materia-theme)
```bash
sudo dnf copr enable tcg/themes
sudo dnf install materia-theme
```

## [La Capitaine Icon Theme](https://github.com/keeferrourke/la-capitaine-icon-theme)
```bash
sudo dnf copr enable tcg/themes
sudo dnf install la-capitaine-icon-theme
```

## [Vim](https://www.vim.org/)
```bash
sudo dnf install vim-enhanced
```

## [Terminator](https://gnometerminator.blogspot.com/p/introduction.html)
```bash
sudo dnf install terminator
```

## [Oh My Zsh](https://github.com/robbyrussell/oh-my-zsh)
Passo-a-passo para [personalização](https://github.com/robbyrussell/oh-my-zsh), por Rodrigo Floriano

Instalando o zsh
```bash
install zsh git
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

Instalando as fontes Powerline
```bash
git clone https://github.com/powerline/fonts.git --depth=1
cd fonts && ./install.sh
cd .. && rm -rf fonts
```

Configurando o terminal
```bash
vim ~/.zshrc
```
Setar o `ZSH_THEME="agnoster"`
Setar a fonte do terminal para `Meslo LG M DZ for Powerline Regular`

## [Autojump](https://github.com/wting/autojump)
```bash
sudo dnf install autojump-zsh
```
