.. :changelog:

Release History
---------------


0.6.5 (2014-12-20)
++++++++++++++++++
- 允许Open Client不传入App参数


0.6.4 (2014-12-20)
++++++++++++++++++
- 添加两个公开的大型新浪微博应用App


0.6.2 (2014-12-14)
++++++++++++++++++
- 调整Token


0.6.0 (2014-12-14)
++++++++++++++++++
- 调整模块架构，分为Open（开放平台）、Web（Web网页）、Wap（手机网页）三种API


0.5.8 (2014-12-13)
++++++++++++++++++
- 支持新浪微博直接登录（直接使用账户密码登录，跳过获取code和回调环节）
- 添加WeicoAndroidApp和WeicoIphoneApp两个App


0.5.7 (2014-12-12)
++++++++++++++++++
- 移除furl
- 更改部分异常类的名称


0.5.6 (2014-12-11)
++++++++++++++++++
- 添加淘宝ApiOAuth2
- 添加ApiResponseValueError


0.5.1 (2014-12-8)
++++++++++++++++++
- 添加豆瓣ApiOAuth2


0.5.0 (2014-12-8)
++++++++++++++++++
- 添加新浪微博、腾讯微博、人人的ApiOAuth2
- 添加淘宝ApiOAuth


0.4.2 (2014-12-7)
++++++++++++++++++
- 移除packages

0.4.0 (2014-12-7)
++++++++++++++++++

- 添加Token，App等models，并添加测试
- 添加ApiClientBase
- 添加ApiError，并添加测试
- 添加新浪微博、腾讯微博、淘宝、人人的ApiClient
- 添加新浪微博、腾讯微博、淘宝、人人的ApiClient本地单元测试（测试成功，因含有帐号信息不上传到Github）


0.3.1 (2014-12-3)
++++++++++++++++++

- 提取共用模块jsonDict，并增加测试


0.3.0 (2013-11-30)
++++++++++++++++++

- 上传到pipy，可通过: pip install chinaapi 进行安装


0.2.0 (2013-11-30)
++++++++++++++++++

**目前已引入的API Python SDK：**

- 新浪微博：https://github.com/michaelliao/sinaweibopy
- 腾讯微博：https://github.com/upbit/tweibo-pysdk
- 淘宝：https://github.com/sempr/taobaopy