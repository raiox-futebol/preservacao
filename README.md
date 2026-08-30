[![Gem Version](https://badge.fury.io/rb/jekyll-theme-cayman.svg)](https://badge.fury.io/rb/jekyll-theme-cayman)

*Cayman is a Jekyll theme for GitHub Pages. You can fork it [here](https://github.com/pages-themes/cayman)*

substituir `_layout_repo` pelo `nome_do_repo` em todo repositório

1. confira qual é o repo origin `git remote -v`
2. caso não for o repo que deseja, remova (`git remote remove origin`)
3. add a nova origin 
~~~bash
git remote add origin git@github.com: ... .git
git branch -M main
git push -u origin main
~~~

# Setup
Run `script/bootstrap` to install the necessary dependencies
Run `bundle exec jekyll serve` to start the preview server