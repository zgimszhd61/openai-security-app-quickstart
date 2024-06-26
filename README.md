# openai-security-app-quickstart
## 指定组件供应链检测
```
你是10年资深组件供应链安全工程师，接下来我将提供给你若干组件，请搜索互联网并分析这些组件是否存在CVE漏洞，如果不存在，返回'no'，不要返回其他内容.如果存在，返回一个表格，分为4列，组件gav，漏洞类别，CVE编号，用中文描述的漏洞原理简介。其中组件如下：
1. langchain
2. llama_index
```

## 24年组件类漏洞检测
```
你是10年资深组件供应链安全工程师，

请搜索互联网并分析2024年有哪些java类别组件出现CVE漏洞。返回一个表格，分为4列，组件gav，漏洞类别，CVE编号，用中文描述的漏洞原理简介。
```


## 安全评审专家
```
会员登录入口需要注意哪些基本的安全要求，请提供一个表格，每一行包含4列，覆盖：模块、需注意的风险点、安全加固建议、验收测试用例
```


## 安全评审流程与实现
1. 用户输入URL.
2. 使用selenium或者puppeteer对URL进行截图.
3. 将截图输入GPT，生成页面介绍和主要元素介绍.
4. 将页面介绍和主要元素介绍输入GPT，得到安全评审报告.
```
我将给你一个网页截图报告，里面包含主要功能和主要元素简介。请帮我分析这个页面需要注意哪些基本的安全要求，请提供一个表格，每一行包含4列，覆盖：模块、需注意的风险点、安全加固建议、验收测试用例

-------------
这是一张ProcessOn登录页面的截图。该页面主要提供用户登录功能，主要元素包括：

ProcessOn标志：页面左上角有ProcessOn的标志。
左侧宣传图：左侧展示了一些ProcessOn的宣传图，图中包含了电脑、手机、云等图形，表示这是一个多设备支持的工具。图下方有用户推荐的评论。
欢迎信息：页面右侧显示“欢迎使用ProcessOn”字样。
登录选项：
账号登录和短信登录选项卡：用户可以选择通过账号或短信登录。
手机号输入框：用户需要输入手机号进行登录，若手机号未输入或不正确会显示“手机号不能为空”的提示。
验证码输入框：用户需要输入收到的验证码，点击“获取验证码”按钮来接收验证码。
登录按钮：输入有效的手机号和验证码后，可以点击“登录”按钮进行登录。
忘记密码和新用户注册链接：提供了忘记密码和新用户注册的选项。
其他登录方式：用户还可以通过微信或QQ进行登录。
这个页面的主要功能是为用户提供便捷的登录途径，使用户能够快速访问ProcessOn的服务。
```

## 基础框架的Quickstart
```
给我一个基于FlowDroid的quickstart
给我一个基于Soot的quickstart
给我一个基于Clang Static Analyzer的quickstart
给我一个基于SonarQube的quickstart
给我一个基于Infer的quickstart
给我一个基于SpotBugs的quickstart
```

## 开源静态代码扫描器的调研
```
我正在做开源静态代码扫描器的调研，请给我提供一个表格，每一行包含7列，覆盖：主要支持的编程语言、影响力（大中小）、开源项目名、开源github地址、基础能力简介、优点、不足。
其中表格里支持主流编程语言覆盖：
1. python
2. java
3. typescript
4. nodejs
5. c/c++
6. rust
7. kotlin
8. swiftui
9. golang
```

## 开源镜像安全扫描器的调研
```
我正在做镜像安全扫描产品的调研，请给我提供一个表格，每一行包含6列，覆盖：开源项目名、影响力（大中小）、开源github地址、基础能力简介、优点、不足。
```


## 供应链安全分析 - java
```
你是世界最顶尖的组件供应链检测工具，你擅长准确地识别pom.xml文件中所使用组件的gav信息，你识别的准确率接近100%
接下来我将提供给你一个pom.xml文件，请返回一个表格，表格里包含2列,组件gav信息，组件简介

----------------
{}
```

## CVE漏洞分析
```
使用最简单的表达方式，说明下面CVE漏洞的基本原理。你将返回一个表格，表格里包含5列，覆盖：CVE编号，CVSS分数、影响的应用或组件、漏洞类别、最简单的原理解释。
其中CVSS编号漏洞包括：
1. CVE 2024-32002
2. CVE-2023-36258
```
