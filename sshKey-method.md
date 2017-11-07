##创建SSH 公私钥方法步骤

1、创建SSH Key：ssh -keygen -t rsa

2、在文件路径 c:\用户\当前用户名\ 找到 .ssh 文件夹

3、文件夹中有两个文件：

​	私钥：id_rsa

​	公钥：id_rsa.pub

4、在 github -> settings -> SSH and GPG keys 页面中，新创建SSH key

5、粘贴 公钥 id_rsa.pub 内容到对应文本框中

6、在 github 中新建仓库或者使用现在仓库，拿到 git@github.com:用户名/仓库名.git

7、此后，再次SSH方式与github “通信”，不用输入密码确认身份了