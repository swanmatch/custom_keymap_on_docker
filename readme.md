# Custom keymap on docker

```sh
# for windows
docker run -v /c/Users/xxxxx/Desktop:/dest -v %CD%:/qmk_firmware/keyboards/silverbullet44/keymaps/custom -e KEYMAP=custom swanmatch/silverbullet44
```
