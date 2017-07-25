
#webpack

###webpack file-loader     

 在webpack中load image文件

####安装 file-loader
>npm install --save-dev file-loader
####配置webpack.config.js

``` 
{test: /\.(jpe?g|png|gif|svg)$/i, loader: "file-loader?name=/public/icons/[name].[ext]"}
```
