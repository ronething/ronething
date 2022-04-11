### Hi there 👋

- 💬 Go, Python, JavaScript 逆向爱好者
- 🎸 热衷指弹
- 🏠 Blog: [blog.ronething.cn](https://blog.ronething.cn)

一些可能比较有(qi)趣(guai)的开源仓库:

#### 数据结构与算法

- [InterviewTips/algorithm-coding](https://github.com/InterviewTips/algorithm-coding): ✍️ 算法写题记录总结
- [InterviewTips/Data-Structures-Java](https://github.com/InterviewTips/Data-Structures-Java): ✍️多种数据结构 涉及一些算法题

![leetcode](https://stats.justsong.cn/api/leetcode?username=ashing&cn=true)

#### Golang(暂未归类)

- [cloud-org/gin-reflect-handler](https://github.com/cloud-org/gin-reflect-handler): gin 编写通用处理函数(基于反射) [相关介绍文章](https://juejin.cn/post/7041916837419810847)
- [cloud-org/over-golang](https://github.com/cloud-org/over-golang): fork 版本，Golang 相关笔记，在原先基础上部署 Gitbook，方便在线阅读
- [cloud-org/kubernetes-notes](https://github.com/cloud-org/kubernetes-notes): kubernetes client-go 相关，包含一些基本的资源操作还有 web container ssh 相关前后端代码等
- [cloud-org/go-git-gitlab-sample](https://github.com/cloud-org/go-git-gitlab-sample): 主要为 [go-git](https://github.com/go-git/go-git) 和 [go-gitlab](https://github.com/xanzy/go-gitlab) 相关操作介绍，代码具体场景：根据提供的 gitlab project id，指定分支或者 tag，以及对应的 commitHash，获取到对应的 git 仓库 url，并克隆到对应的目录
- [cloud-org/reflect-sample](https://github.com/cloud-org/reflect-sample): 反射的相关应用，编写通用的 mongo 操作类，例如创建更新操作自动新增字段赋值当前时间等。
- [cloud-org/gocn-push](https://github.com/cloud-org/gocn-push): gocn 每日新闻推送，目前支持的推送方式有三种，分别为: 企业微信、钉钉、Slack
- [cloud-org/go-template](https://github.com/cloud-org/go-template): Go 项目通用模版，不过目前只是支持 pre-commit 和 LICENSE 之类
- [cloud-org/broadcast](https://github.com/cloud-org/broadcast): 📢 结合 etcd watchChan 做配置变更广播，具体场景为多个 agent 连接 server，server 启动一个 watchChan 监听 etcd 某个 key 或者 --prefix，然后有事件通知则循环广播通知所有的 agent
- [cloud-org/6.824](https://github.com/cloud-org/6.824): MIT6.824 分布式系统课程，坑还没填完，目前暂时只写了实验一 MapReduce
- [cloud-org/beats-output-http](https://github.com/cloud-org/beats-output-http): 编译  filebeat v7.13.0 add http output
- [cloud-org/beats-output-http-another](https://github.com/cloud-org/beats-output-http-another): 另一个编译  filebeat v7.13.0 add http output
- [cloud-org/delay-task-scheduler](https://github.com/cloud-org/delay-task-scheduler): 延时任务调度器 重点在于时间轮的实现，这里参考了 [rfyiamcool/go-timewheel](https://github.com/rfyiamcool/go-timewheel) 的实现并进行一些 bug 修复
- [cloud-org/kafka-golang-sample](https://github.com/cloud-org/kafka-golang-sample): [kafka-go](github.com/segmentio/kafka-go) 的相关使用以及注意点
- [cloud-org/grpc-auth-sample](https://github.com/cloud-org/grpc-auth-sample): gRPC 认证相关 可参考相关[文章](https://juejin.cn/post/7041603440841064461)介绍
- [cloud-org/shellcheck-web-wrapper](https://github.com/cloud-org/shellcheck-web-wrapper): [shellcheck](https://github.com/koalaman/shellcheck) 的 web 包装，提供一个 HTTP 服务方便用户接入
- [cloud-org/multi-timezone-scheduler](https://github.com/cloud-org/multi-timezone-scheduler): 多时区定时任务调度器 基于 [cronv3](https://github.com/robfig/cron) 其实本身参数是有支持的(逃
- [cloud-org/crontab](https://github.com/cloud-org/crontab): 支持多 master 多 worker 的定时任务调度组件
- [cloud-org/go-demo](https://github.com/cloud-org/go-demo): mongo、etcd client 模块的相关 demo 操作
- [ronething/clock](https://github.com/ronething/clock): 基于 redis 和 mongodb 实现分布式任务调度组件，集成 prometheus 监控
- [ronething/mp-dev](https://github.com/ronething/mp-dev): 微信公众号开发，通过路由文本实现不同功能回复
- [ronething/wechat-bot-go](https://github.com/ronething/wechat-bot-go): 微信个人机器人客户端封装

#### Python

- [ronething/ZhiHuCollectionToPDF](https://github.com/ronething/ZhiHuCollectionToPDF): 知乎收藏夹导出成 PDF 文档
- [ronething/ZhiHuZhuanLanToPDF](https://github.com/ronething/ZhiHuZhuanLanToPDF): 知乎专栏文章导出成 PDF 文档
- [ronething/mp-music](https://github.com/ronething/mp-music): 微信公众号 音乐 API 接入

#### Misc(杂项)

- [cloud-org/lua-in-action](https://github.com/cloud-org/lua-in-action): 看看 lua
- [cloud-org/es6-in-action](https://github.com/cloud-org/es6-in-action): 看看 js
- [ronething/ifttt](https://github.com/ronething/ifttt): [ruanyf/weekly](https://github.com/ruanyf/weekly) 科学爱好者周刊订阅推送(基于 [actionsflow](https://github.com/actionsflow/actionsflow))

#### Coding

<!--START_SECTION:waka-->
![Profile Views](http://img.shields.io/badge/Profile%20Views-71-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-462%20Thousand%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 349 Contributions in the Year 2022
 > 
> 📦 721.9 kB Used in GitHub's Storage 
 > 
> 🚫 Not Opted to Hire
 > 
> 📜 122 Public Repositories 
 > 
> 🔑 48 Private Repositories  
 > 
**I'm a Night 🦉** 

```text
🌞 Morning    38 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.41% 
🌆 Daytime    147 commits    █████████░░░░░░░░░░░░░░░░   36.39% 
🌃 Evening    140 commits    ████████░░░░░░░░░░░░░░░░░   34.65% 
🌙 Night      79 commits     █████░░░░░░░░░░░░░░░░░░░░   19.55%

```
📅 **I'm Most Productive on Saturday** 

```text
Monday       42 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.4% 
Tuesday      43 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.64% 
Wednesday    55 commits     ███░░░░░░░░░░░░░░░░░░░░░░   13.61% 
Thursday     41 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.15% 
Friday       43 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.64% 
Saturday     103 commits    ██████░░░░░░░░░░░░░░░░░░░   25.5% 
Sunday       77 commits     ████░░░░░░░░░░░░░░░░░░░░░   19.06%

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Asia/Shanghai

💬 Programming Languages: 
Go                       2 hrs 38 mins       ██████████████████████░░░   88.42% 
YAML                     19 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   10.9% 
Dockerfile               0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.34% 
GitIgnore file           0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.26% 
Markdown                 0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.04%

🔥 Editors: 
IntelliJ                 2 hrs 59 mins       █████████████████████████   100.0%

💻 Operating System: 
Mac                      2 hrs 59 mins       █████████████████████████   100.0%

```

**I Mostly Code in Go** 

```text
Go                       34 repos            ██████████░░░░░░░░░░░░░░░   41.46% 
Python                   21 repos            ██████░░░░░░░░░░░░░░░░░░░   25.61% 
Vue                      6 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   7.32% 
Java                     5 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   6.1% 
Jupyter Notebook         4 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   4.88%

```



 Last Updated on 11/04/2022 02:27:52 UTC
<!--END_SECTION:waka-->
