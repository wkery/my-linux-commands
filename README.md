# Linux常用命令

#### ls 显示目录文件
    ls  显示当前目录下文件
    ls 文件名  指定前目录下文件

#### cd 切换所在目录
    cd /user/src  进入指定目录（绝对路径）
    cd ~  进入当前用户的家目录
    cd .. 进入上一级目录
    cd -  进入上一次目录

#### pwd 显示当前所在目录（当前工作目录）

##### Linux常见目录：
    / 根目录
    /etc 配置文件保存目录
    /user 系统软件资源目录
    /root 超级用户的家目录
    /bin  命令保存目录
    /lib  系统库保存目录
    
#### mkdir 创建目录
    mkdir test 创建名为test的目录
    mkdir -p test1/test2/test3  递归创建目录
    
#### rmdir 删除目录（只能删除空目录）
#### touch 创建空文件或修改文件时间
    touch index.html  创建空文件，如果文件存在则修改文件创建时间
    
#### rm 删除文件或目录
    rm 文件名  删除文件
    rm -r 目录名 递归删除文件和目录
    rm -f 文件名 强制删除
    rm -rf 目录名  强制删除目录和文件
    
#### cat 查看文件内容
    cat 文件名 查看文件内容
    cat -n 文件名  查看文件内容，并列出行号
    
#### cp 复制文件或目录
    
