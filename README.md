# Fat-Free Framework snippets for Sublime Text 2


Installing
----------
**With the Package Control plugin:** The easiest way to install Fat-Free Snippets is through Package Control, which can be found at this site: http://wbond.net/sublime_packages/package_control

Once you install Package Control, restart ST2 and bring up the Command Palette (`Command+Shift+P` on OS X, `Control+Shift+P` on Linux/Windows). Select "Package Control: Install Package", wait while Package Control fetches the latest package list, then select Fat-Free Snippets when the list appears. The advantage of using this method is that Package Control will automatically keep Fat-Free Snippets up to date with the latest version.

![img](http://iceimg.com/i/5c/85/b6ecbbe2aa.png)

**Without Git:** Download the latest source from [GitHub](https://github.com/uonick/fatfree-snippets) and copy the Fat-Free Snippets folder to your Sublime Text "Packages" directory.

**With Git:** Clone the repository in your Sublime Text "Packages/User" directory:

    git clone https://github.com/uonick/fatfree-snippets.git


The "Packages" directory is located at:

* OS X:

        ~/Library/Application Support/Sublime Text 2/Packages/User

* Linux:

        ~/.config/sublime-text-2/Packages/User

* Windows:

        %APPDATA%\Sublime Text 2\Packages\User

## How to use:
### Just type:

* `fse` [TAB]
```
$f3->set(key,value);
```

* `fge` [TAB]
```
$f3->get('param');
```
etc..

### OR
Press `Ctrl+Shift+P`, type `fat` and select snippet

## Links:

[Fat-Free Framework](https://github.com/bcosca/fatfree) on GitHub

[Aviable snippets:] (https://github.com/uonick/fatfree-snippets/wiki/Snippets)


