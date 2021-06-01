# cliExample

参考链接：[从 0 构建自己的脚手架知识体系（万字）](https://juejin.cn/post/6966119324478079007)

创建流程

1. 建立package.json

  npm init

  ```json
  {
      "name": "cliExample",
      "version": "1.0.0",
      "description": "",
      "main": "cli.js",
      "bin": "cli.js",
      "scripts": {
          "test": "echo \"Error: no test specified\" && exit 1"
      },
      "author": "",
      "license": "ISC",
      "dependencies": {
          "ejs": "^3.1.6",
          "inquirer": "^8.1.0"
      }
  }
  ```

2. 建立执行文件

  对应上方cli.js

  可建立模板文件，对文件进行读写等操作

3. 链接到全局

  npm link

  可在全局执行命令，对应上方cliExample

4. 执行命令即可搭建自定义脚手架
