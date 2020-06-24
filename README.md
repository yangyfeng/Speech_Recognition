author:hanyang
## 运行
1.打开cmd，进入demo目录，执行如下命令
 ```
cd src
python3 -m http.server 5063
或者 python -m http.server 5063
 ```
2.在chrome浏览器中打开返回的地址，例如
http://127.0.0.1:5063/index.html
 
## 注意事项
1.请使用chrome浏览器测试。
2.生成的语音流是16k 16bit的pcm数据，后端识别引擎需要与之匹配


