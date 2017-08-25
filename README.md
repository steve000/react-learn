# react-learn
react学习，持续集成，一直更新

```
mkdir react-learn
cd react-learn

npm install 

npm start
```
浏览器访问 localhost:404

> 2017-08-19
1. 工程构建
2. 添加webpack打包，编译jsx、scss
3. 集成了amazeui-touch，作为UI库

> 2017-08-20
1. 添加react-router，版本2.4.1

> 2017-08-24
1. 集成flux，Index组件点击 Default Buttom 改变第一个Group标题（手机号码）

> 2017-08-25
1. 使用nginx实现跨域 </br>
本机ip 192.168.1.168 </br>
cd  /nginx  </br>
start nginx.exe
2. 测试： Index组件点击 Default Buttom，触发ajax请求，代理到http://192.168.1.239:8080