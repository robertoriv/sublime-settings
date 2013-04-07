## README ##

1. Clone the git repository to a local folder: ` $ git clone git@github.com:robertoriv/sublime-settings.git`

2. __cd__ into _Sublime Text's __Packages___ Folder: ` $ cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages`

3. Delete old ` Users/` folder: ` $ rm -rf User/`

4. Create the symbolic link, so that the **User** folder points back to the cloned repo: ` $ ln -s ~/code/sublime-settings/ User`