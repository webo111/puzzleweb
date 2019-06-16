# puzzleweb

> 有一个github账号，没有的话去注册一个；
> 安装了node.js、npm，并了解相关基础知识；
> 安装了git for windows（或者其它git客户端）

$ npm install -g hexo

$ hexo init
#### 添加theme
$ git clone https://github.com/hexojs/hexo-theme-landscape.git themes/landscape

$ hexo g # 生成

$ hexo s # 启动服务

```
# URL
## If your site is put in a subdirectory, set url as 'http://yoursite.com/child' and root as '/child/'
## 配置二级路径为根路径
url: https://webo111.github.io/puzzleweb
root: /puzzleweb/

deploy:
  type: git
  repo: https://github.com/webo111/puzzleweb.git
  branch: gh-pages
```

$ npm install hexo-deployer-git --save

$ hexo deploy

## 常见命令
```
hexo new "postName" #新建文章
hexo new page "pageName" #新建页面
hexo generate #生成静态页面至public目录
hexo server #开启预览访问端口（默认端口4000，'ctrl + c'关闭server）
hexo deploy #部署到GitHub
hexo help  # 查看帮助
hexo version  #查看Hexo的版本
```
### 缩写：
```
hexo n == hexo new
hexo g == hexo generate
hexo s == hexo server
hexo d == hexo deploy
```

