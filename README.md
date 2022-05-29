# nvim-config
My neovim init.vim configuration file.

Installation process:

1)  At first:<br>
`brew install nvim` <br>
`npm install --location=global pyright`

2)  Check the Neovim installation (optional): <br>
`:checkhealth` <br> If needed - fix missing packages and settings.
 
3)  Neovim settings will be stored at `~/.config/nvim/init.vim` file:<br>
`mkdir ~/.config/nvim`<br>  
`cd ~/.config/nvim`<br>  
`touch init.vim`

4)  Pip install for Neovim:<br>
`pip install neovim`<br>
`pip install pynvim`

5)  Replace init.vim

6)  Update and install plugins:
`:PlugInstall`

7)  install Co-python (optional):
`:CocInstall coc-python`
