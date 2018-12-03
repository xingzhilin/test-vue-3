#  server.js  --  入口文件
#  自动保存
  sudo npm install nodemon -g


# 依赖
   - "bcrypt": "^2.0.1",  // 密码加密处理
   - "body-parser": "^1.18.3",  // 用来解析post的请求取代了 原生的 req.on 的方式 但是只能取到ajax 和表单的数据 ，取不到上传的文件类型。
   - "express": "^4.16.3", // node开发框架
   - "gravatar": "^1.6.0", // 头像
   - "jsonwebtoken": "^8.2.1",  // 生成token -- 待测试
   - "mongoose": "^5.1.0", // 数据库
   - "passport": "^0.4.0", //进行本地【用户名+密码】鉴权
   - "passport-jwt": "^4.0.0", // passport-jwt和passport中间件来验证token，passport-jwt是一个针对jsonwebtoken的插件，passport是express框架的一个针对密码的中间件
   - "validator": "^10.2.0"  // 在javascript中验证对象属性
