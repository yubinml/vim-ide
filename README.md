### Summarize
* **requirements：** 
    * vim 7.1 or higher, support linux、mac、cygwin.
* **feature：** 
    * read and write c/c++/python project.
* **difference：** 
    * one command to install and it's pure green

### Install And Update
* **centos, redhat, fedora install command:**
    * yum install ctags cscope wget unzip -y && wget https://github.com/langsim/vim-ide/archive/master.zip -O master.zip && unzip -o master.zip && rm -rf ~/.vim && \cp -rf vim-ide-master/.vim* ~ ; rm -rf master.zip vim-ide-master
* **debian, ubuntu install command:**
    * apt-get install ctags cscope wget unzip -y && wget https://github.com/langsim/vim-ide/archive/master.zip -O master.zip && unzip -o master.zip && rm -rf ~/.vim && \cp -rf vim-ide-master/.vim* ~ ; rm -rf master.zip vim-ide-master

### Do Project
* **open project:**
    * cd into project root dir,vim (press enter). press F2 to open file tree.
* **update index:**
    * when first time open project, press F5 to update index.(only in c/c++)
* **custom function:**
    * **"F2":** open file tree
    * **"F3":** display variable and function list
    * **"F4":** switch include file and implement file
    * **"F5":** update index
    * **"F6":** display invisible character or not 
    * **"F7":** highlight word under the cursor
    * **"F8":** opened file list
    * **"F9":** set paste!
    * **"F10":** display variable and function list
    * **",":** comment selected code
    * **".":** uncomment selected code
    * **"ctrl-left":** move cursor to left window in vim
    * **"ctrl-right":** move cursor to right window in vim
    * **"ctrl-]":** jump to function or non-local variable defination
    * **"ctrl-[ s":** search variable or function in project (only in c/c++)

### Hope
* consuming less brain, less finger and less cpu to read and write code.

### 简介
* **系统要求：** 
    * vim 7.1或以上，支持inux、mac、cygwin.
* **用途：** 
    * 阅读和编写c/c++/python项目.
* **特点：** 
    * 一个命令纯绿色安装

### 安装与更新
* **centos, redhat, fedora:**
    * yum install ctags cscope wget unzip -y && wget https://github.com/langsim/vim-ide/archive/master.zip -O master.zip && unzip -o master.zip && rm -rf ~/.vim && \cp -rf vim-ide-master/.vim* ~ ; rm -rf master.zip vim-ide-master
* **debian, ubuntu:**
    * apt-get install ctags cscope wget unzip -y && wget https://github.com/langsim/vim-ide/archive/master.zip -O master.zip && unzip -o master.zip && rm -rf ~/.vim && \cp -rf vim-ide-master/.vim* ~ ; rm -rf master.zip vim-ide-master


### 使用说明
* **打开项目:**
    * 打开项目根目录，输入vim回车，然后按F2键打开文件列表.
* **更新索引:**
    * 第一次打开项目，按F5更新索引.(只有c/c++项目需要)
* **定制功能:**
    * **"F2":** 打开文件树
    * **"F3":** 显示变量和函数列表
    * **"F4":** 切换头文件与实现文件
    * **"F5":** 更新索引
    * **"F6":** 切换是否显示隐藏字符
    * **"F7":** 高亮光标下单词
    * **"F8":** 已打开的文件列表
    * **"F9":** set paste!
    * **"F10":** 退出vim
    * **",":** 注释选中的代码
    * **".":** 将选中的注释代码解注释
    * **"ctrl-left":** 把光标移动到左边的窗口
    * **"ctrl-right":** 把光标移动到右边的窗口    
    * **"ctrl-]":** 跳转到函数或全局变量的定义
    * **"ctrl-[ s":** 在整个项目中搜索某个变量或函数 (只适用于c/c++)


### 愿景
* 以更少的逻辑思维量，更少的手指运动量，并消耗更少的CPU来编写代码
