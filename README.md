# QQ

参考你所使用的系统安装包管理器的使用说明来安装你所选择的Linux QQ安装程序，注意你需要root权限才能完成安装。在一些发行版中你可以通过双击文件管理器中的安装程序完成安装。以下是一些使用命令行来安装的例子：

sudo ./linuxqq_1.0.1-b1-100_x86_64.sh
sudo rpm -ivh linuxqq_1.0.1-b1-100_mips64el.rpm
sudo dpkg -i linuxqq_1.0.1-b1-100_armhf.deb
sudo apt install -y /path/to/linuxqq_1.0.1-b1-100_amd64.deb
sudo pacman -U linuxqq_1.0.1-ci-94_x86_64.pkg.tar.xz



如果版本更新后登录出现闪退情况，请删除 ~/.config/tencent-qq/#你的QQ号# 目录后重新登录。
