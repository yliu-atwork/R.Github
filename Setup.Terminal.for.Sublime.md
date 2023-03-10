# Set up terminal for Sublime shortcut"
### Adapted from https://gist.github.com/barnes7td/3804534"

# Level 1 text
## Level 2 text
### Level 3 text
#### Level 4 text
##### Level 5 text
* text1 
1. point 1
2. point 2
3. point 3
* text2
(1) point 1
(2) point 2
(3) point 3
* text3

*italics*

**bold**

Let's make <span style="color:red">this red</span>

## Quarto

Quarto enables you to weave together content and executable code into a finished document. To learn more about Quarto see <https://quarto.org>.

## Running Code

When you click the **Render** button a document will be generated that includes both content and the output of embedded code. You can embed code like this:


## Create a directory at ~/bin
```
mkdir ~/bin
```

## Copy sublime executable to your ~/bin directory: (Turns out I have ZSH on my MacBook, even though I don't know what it is)
```
ln -s "/Applications/Sublime Text.app/Contents/SharedSupport/bin/subl" ~/bin/subl
ZSH 
```

## If using zsh add line to ~/.zshrc file:
```
echo 'export PATH=$PATH:$HOME/bin' >> ~/.zshrc
```

## Set sublime as your default editor:
```
echo "export EDITOR='subl -w'" >> ~/.zshrc
```

## Restart terminal and type:
```
subl .
```

## Check unix commands:
```
ls
```

