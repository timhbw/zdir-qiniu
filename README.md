# zdir-qiniu
### 详细使用说明可以查看原作者仓库[文档](https://github.com/helloxz/zdir)

### 效果展示

* 网站截图![zdir-qiniu](https://app.dlcdn.timhbw.com/zdir-qiniu-001.png)
* 七牛后台截图![zdir-qiniu](https://app.dlcdn.timhbw.com/zdir-qiniu-002.png)

### 我修改的地方
* 前端页面点击文件名后的下载链接是七牛云kodo（对象存储）的外链地址；
* 文件名右侧的下载按钮，下载链接是七牛云kodo（对象存储）的外链地址。

### 优点
* 降低服务器负载。即使使用1核1G1M 配置的服务器，当用户下载资源时，服务器也不会告警，因为下载全部走七牛云服务，您自己的服务器只提供前端页面。
* 提升用户下载体验。之前如果您的服务器带宽为 1 M，那么用户本地的下载速度最高也就只有 100kb 左右了，但使用七牛云存储后，结合七牛云的融合 CDN，用户下载速度得到大幅提升！

### 使用文档
[前往我的博客查看 - 等后续补上，先占位](https://timhbw.com/xx.html)

### 注册七牛
* [注册链接-含aff](https://portal.qiniu.com/signup?code=1hfwbbz516dzm)
* [注册链接-不含aff](https://portal.qiniu.com/signup)
