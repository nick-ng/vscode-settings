# ToDo
* Don't install programs if they're already installed (e.g. running again to update settings).
    * `which code | grep "not found" >/dev/null && echo "hi"`
* Change keyboard shortcuts so they don't use Alt as much.
# Steps
* Install git and checkout repo
```
sudo apt install -y git && git clone https://github.com/nick-ng/dev-settings.git ~/gits/dev-settings && cd ~/gits/dev-settings
```
* Run script
```
source kde.sh
```
## Github
* Add SSH key to Github
    * Click on your face -> settings -> SSH and GPG keys
```
cat ~/.ssh/id_rsa.pub | xclip -selection clipboard
```
## Node.js
```
source node.sh
```
## Mac
* bash_aliases
* karabiner.json
* vs-code.json
* [Karabiner Elements Complex Modifications](karabiner://karabiner/assets/complex_modifications/import?url=https://raw.githubusercontent.com/nick-ng/dev-settings/master/karabiner_complex.json)

