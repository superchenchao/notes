### NPM如何发布自己的升级包

  npm unpublish --force

  npm publish

### NPM开启cnpm镜像

  npm config set registry http://registry.cnpmjs.org     //配置指向源,通过`nrm ls`查看源;

### npm关掉cnpm镜像

  npm config delete registry
  
  npm config delete disturl
  
### NPM查看当前用户

  npm whoami     

### 查看配置文件
  
  npm config edit                             //打开.npmrc文件;

### npm安装指定版本

  npm install lodash@3.8.0
