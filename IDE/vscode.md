自动换行：文件->首选项->设置："editor.wordWrap": "on"

---

vscode需要设置等宽字体，否则使用体验会非常差，比如tab键，四个空格和两个字母的大小相当，影响观感。

Source Code Pro就是一种等宽字体，在ubuntu下的安装步骤为：

sudo mkdir /usr/share/fonts/opentype

sudo git clone https://github.com/adobe-fonts/source-code-pro.git /usr/share/fonts/opentype/scp

sudo fc-cache -f -v

在电脑上安装好Source Code Pro后，设置vscode的Editor：Font Family为'Source Code Pro'即可

***

___
