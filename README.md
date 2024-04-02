# 声明
此项目根据开源项目vue-admin-template更改而来，主要基于该项目进行了小部分更改以便快速创建一个前端项目。
# 新增
* 增加容器打包配置，使用Nginx运行。
* 添加了部分配置、代码的注释。
# 开发环境调试
建议使用vscode进行开发调试。
1. 安装依赖
```shell
npm install
```
2. 运行项目
```shell
npm run dev
```
项目运行成功后默认监听9258端口，如果想变更端口可参考`vue.config.js`文件中名为`port`常量的相关使用说明。
# 生产环境部署
1. 安装依赖
```shell
npm install
```
2. 项目编译
```shell
npm run build:prod
```
3. 打包镜像
打包镜像参考`Dockerfile`文件中的配置即可，可根据自己的喜好更改。
# 项目基本使用
## 更改项目标题
修改`src/settings.js`文件中的`title`名称。

