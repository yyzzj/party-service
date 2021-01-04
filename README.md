# zhsj_old

## 项目简介
本项目为老年人客户端，基于MPA架构搭建的学生与教师端应用🚀🚀🚀

## 项目相关库链接
### Mockjs：一个用于本地mock的简易api库 🎉
> http://mockjs.com/
### videojs：提供良好的移动端视频播放组件 🎐
> https://videojs.com/ 
### storybook：用于搭建组件沙箱环境 🤿
> https://storybook.js.org/
### puppeteer：用于自动化测试 🐛
> https://github.com/puppeteer/puppeteer


## 本项目相关命令

### 项目依赖安装
```
npm install
```

### 项目本地运行
```
npm run serve
```

### 运行组件沙箱
```
npm run storybook
```

### 生产环境打包
```
npm run build
```

### eslint自动校对
```
npm run lint
```

## 版本管理

### 分支规范
* `master`: 主分支，发布生产环境使用的唯一分支。推送时会触发CI构建，但不会自动发布，需要手动发布。
* `test`：测试分支，发布测试环境使用的唯一分支。
* `dev`：开发分支，项目主要开发分支，多人参与开发时，可各自创建工作分支，并定时同步 dev 分支。

### commit规范
* `feat`：新功能
* `fix`：修补 bug
* `docs`：文档
* `style`：格式
* `refactor`：重构
* `test`：增加测试
* `chore`：构建过程或辅助工具的变动
* 示例：</br>
 feat: 新增××模块/页面</br>
 fix: ××接口异常问题

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
