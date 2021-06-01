# 代码打开和使用
- cd /e
- mkdir porject
- git config --global user.emal 1574231611@qq.com
- git config --global user.name"xwhnjdn"
- git config --global url."https://github.com.cnpmjs.org/".insread Of"https://github.com/"
- git clone https://github.com/xwhnjdn/markdown.git
- cd markdown
- code .

# 代码上传
- git add .
- git config --global user.emal 1574231611@qq.com
- git config --global user.name"xwhnjdn"
- git commit -m "注释"
- git push -u origin main
- 若出错则加入代码：git config --global http.sslVerify "false"