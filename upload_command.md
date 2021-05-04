#### 最基本的上传步骤  
如下代码按顺序敲即可
```
git init
git remote add origin git@gitthub.com:plusru/exam.git //"plusru"为注册用户名，"eaxm"是创建的仓库名
git pull git@gitthub.com:plusru/exam.git //同步仓库内容到本地
git add . //add后面的点，表示的是提交所有文件，如果想指定提交文件，可以写文件名
git commit -m "xxxxxx" //-m后面是提示信息
git push git@gitthub.com:plusru/exam.git //推送本地文件到github仓库
```
