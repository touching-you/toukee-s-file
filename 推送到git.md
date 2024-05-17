1. 安装git

2. 初始化本地仓库

   在本地仓库打开命令行输入：

   ```bash
   git init
   ```

3. 设置密钥和公钥

   1. 本地创建**.ssh**文件夹

   2. git bash输入：

      ```bash
      ssh-keygen -t rsa -C "youremail@example.com" 
      ```

      然后不断回车

   3. 将生成的公钥粘贴到github

      登陆github，点击个人账户**settings**，点击**SSH and GPG keys**

4. 创建仓库

   在github首页创建仓库

5. 将项目推送到远程仓库

6. 将远程项目更新到本地

7. 