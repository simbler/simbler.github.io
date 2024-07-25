# simbler.github.io

## making changes 

### adding clips
1. go to the `clips.markdown` file in [edit mode](https://github.com/simbler/simbler.github.io/edit/main/docs/clips.markdown)
2. add your clips in the following format:
```    
[Clip Title](clip-link.com)
```
3. check your update by clicking the "Preview" tab
4. when you're ready, hit the green "Commit changes" button 

### formatting text 
for other text formatting changes, see this [markdown guide](https://guides.github.com/features/mastering-markdown/)

### customizing style 
custom css can be added to `docs/_includes/head.html`. see jekyll's [minima theme docs](https://github.com/jekyll/minima#customizing-templates) for more.

## local usage

1. install dependencies and serve content (recommend developing in a container, such as with [vscode](https://code.visualstudio.com/docs/devcontainers/containers)):
```
sudo snap install bundle
sudo apt-get update
sudo apt-get install ruby ruby-dev
sudo gem install bundler

cd docs
sudo bundle update
bundle exec jekyll serve
```
2. go to `http://localhost:4000/`
