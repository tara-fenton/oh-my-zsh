### Oh-My-Zsh!
First, we will change the default "shell" or terminal environment to use one that is more friendly for developers.

Open the `Terminal` app and type the following two commands (Hit `<Enter>` after each):
```
brew install zsh zsh-completions
```

Verify installation by running `zsh --version`. Expected result: zsh 5.1.1 or more recent.

Make it your default shell: 
* Open terminal preferences <kbd>⌘</kbd> <kbd>,</kbd>
* Click the 'General' Tab
* Click 'Shell opens with Command (complete path)'
* Type `/bin/zsh` inside the text field

Log out and login back again to use your new default shell.
Test that it worked with 
```echo $SHELL```

Expected result: /bin/zsh or similar.

Install oh-my-zsh 
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```
