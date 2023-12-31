## LsJudgeQuestion
## 在线判题系统

### 介绍
基于Spring Boot＋MySQL + Docker的编程题目评测系统。系统能够根据管理员预设的题目用例对用户提交的代码进行执行和评测；<br/>
系统中自主实现的代码沙箱可作为独立服务供其他开发者调用。<br/>

### 功能
1. 用户模块
- 注册
- 登录

2. 题目模块
- 创建题目(管理员)
- 删除题目(管理员)
- 修改题目(管理员)
- 搜索题目(用户)
- 在线做题
- 提交题目代码
- 判断代码沙箱的返回结果，更新题目状态

3. 判题模块
- 提交判题(结果是否正确与错误)
- 错误处理(内存溢出、安全性、超时)
- 自主实现代码沙箱(安全沙箱)
- 封装返回执行结果
