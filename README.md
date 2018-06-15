# Angular
记录在工作中遇到的坑
问题：ng g c name时，用ng创建模块，组件，服务...，报错：Angular 1.4.9 : Cannot read property 'NullLogger' of undefined

解决办法：
npm install --save-dev @angular-devkit/core@latest
npm install --save-dev @angular-devkit/schematics@latest
