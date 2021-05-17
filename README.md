# How to Use

- Clone the repo in: `$HOME/projects/zprezto-contrib`
- Create a link: `ln -s projects/zprezto-contrib .zprezto-contrib`
- Uncomment `.zprezto-contrib` usage in `.zpreztorc`
```
zstyle ':prezto:load' pmodule-dirs $HOME/.zprezto-contrib
```
- Activate contrib modules
```
zstyle ':prezto:load' pmodule \
  ...
  ...
  'contrib-env' \
  'contrib-aliases'
```
