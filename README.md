# wechat-tnwz
## 微信小程序--头脑王者辅助
### 适用安卓和苹果
### - 注意本工具仅供辅助娱乐，不可用于商业用途
#### - 本辅助正确率大概在百分之七八十左右，答案仅供参考

## 使用原理
利用http/https代理服务,对头脑王者的接口请求进行截获,主要作用有：
- 将题目和返回的标准答案存储于数据库中，匹配出最优解
- 未匹配到标准答案情况下，自动请求搜索引擎，注解形式返回最佳概率结果


### 手机操作步骤
- 首先，安装证书，下载证书`cert.crt`文件 或者 链接: [证书下载](http://t.cn/RQQyIGC) 密码: `ke16`
- 不同手机会有不同的安装方式，建议小白搜索下自己机型如何安装证书
  - IOS记得要信任证书 (`cert.crt`传到手机中, 点击安装证书)
  - 我以一加手机为例：设置——安全和锁屏——凭据存储——从储存设备安装——选择手机文件中的cert.crt文件
- 其次，修改代理，需要连接WiFi网络，长按已连接WiFi名称，修改网络，高级选项，代理，主机为 `tnwz.dazheniao.com` , 端口为 `8998`
- 打开头脑王者进入答题，正确的答案将在选项中以【标准答案】或【数字】字样，效果下图

  <div align="center">
    <img src="https://github.com/sowee121/wechat-tnwz/raw/master/wechat.jpg" width="400">
  </div> 


