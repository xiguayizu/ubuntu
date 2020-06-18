# ubuntu
ubuntu 装机 android8.0编译环境

ubuntu安装时选中文可自带安装输入法

## Ubuntu实时监控网速、CPU、内存

sudo add-apt-repository ppa:fossfreedom/indicator-sysmonitor
sudo apt-get update
sudo apt-get install indicator-sysmonitor

indicator-sysmonitor &

然后`Ctrl+C`就可以实现后台运行indicator-sysmonitor。
为程序添加开机启动！鼠标右键点击标题栏上图标，弹出菜单，选择首选项，在弹出的界面选中`Run on Startup`
在`高级`标签页中输入`{net} C{cpu} M{mem}`就可以在标题栏显示上下行网速、CPU和内存的使用情况，也可以自定义显示的内容。

## 添加开机启动

gedit ~/.bash_login

## 预备安装软件
>>>
sudo apt-get install -y git flex bison gperf build-essential libncurses5-dev:i386
sudo apt-get install libx11-dev:i386 libreadline6-dev:i386 libgl1-mesa-dev g+±multilib
sudo apt-get install tofrodos python-markdown libxml2-utils xsltproc zlib1g-dev:i386
sudo apt-get install dpkg-dev libsdl1.2-dev libesd0-dev
sudo apt-get install git-core gnupg flex bison gperf build-essential
sudo apt-get install zip curl zlib1g-dev gcc-multilib g+±multilib
sudo apt-get install libc6-dev-i386
sudo apt-get install lib32ncurses5-dev x11proto-core-dev libx11-dev
sudo apt-get install lib32z-dev ccache
sudo apt-get install libgl1-mesa-dev libxml2-utils xsltproc unzip m4x
sudo apt-get  install xmllint
sudo apt-get  install libxml2-utils

### chrome
sudo add-apt-repository ppa:a-v-shkop/chromium
sudo apt-get update
sudo apt-get install chromium-browser


