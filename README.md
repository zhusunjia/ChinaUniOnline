# 中国大学生在线 “四史”学习教育竞答 自动答题 刷分 (3.18可用)  
## 若对您有所帮助，记得点个Star🌟！！！ 
 
 

## 感谢[@zhanghua000](http:\/\/github.com\/zhanghua000)小伙伴对本项目的可视化以及维护和更新!🥰


## 特别声明:

* 本仓库发布的`ChinaUniOnline`项目中涉及的任何脚本，仅用于测试和学习研究，禁止用于商业用途，不能保证其合法性，准确性，完整性和有效性，请根据情况自行判断。

* 本项目内所有资源文件，禁止任何公众号、自媒体进行任何形式的转载、发布。

* `Upsetin` 对任何脚本问题概不负责，包括但不限于由任何脚本错误导致的任何损失或损害.

* 间接使用脚本的任何用户，包括但不限于建立VPS或在某些行为违反国家/地区法律或相关法规的情况下进行传播, `Upsetin` 对于由此引起的任何隐私泄漏或其他后果概不负责。

* 请勿将`ChinaUniOnline`项目的任何内容用于商业或非法目的，否则后果自负。

* 如果任何单位或个人认为该项目的脚本可能涉嫌侵犯其权利，则应及时通知并提供身份证明，所有权证明，我们将在收到认证文件后删除相关脚本。

* 以任何方式查看此项目的人或直接或间接使用`ChinaUniOnline`项目的任何脚本的使用者都应仔细阅读此声明。`Upsetin` 保留随时更改或补充此免责声明的权利。一旦使用并复制了任何相关脚本或`ChinaUniOnline`项目，则视为您已接受此免责声明。
  
* 您必须在下载后的24小时内从计算机或手机中完全删除以上内容。  

> ***您使用或者复制了本仓库且本人制作的任何代码或项目，则视为`已接受`此声明，请仔细阅读***  
> ***您在本声明未发出之时点使用或者复制了本仓库且本人制作的任何代码或项目且此时还在使用，则视为`已接受`此声明，请仔细阅读***


### 依赖
本项目依赖的第三方库:  
`requests`  

在终端执行以下语句安装依赖即可:  
`pip install requests`  

#### 使用方法
#### 运行后直接输入token或uid即可，程序会自动识别。 
#### ⚠️ ️注意:
#### ️输入token为Bearer后面那一串英文，一定要复制完全！
+ 有Python环境  
  将题库.csv与main.py放于同一目录下,直接运行main.py文件即可.
  
+ 无Python环境
  下载可执行文件，将题库.csv与main.exe置于同一文件夹，直接运行即可.
  
### 关于uid或token的获取
#### 在微信中访问链接 https://open.weixin.qq.com/connect/oauth2/authorize?appid=wxe12424c3b8aad5e6&redirect_uri=https://core.u.hep.com.cn/oauth/wechatmp/redirect&response_type=code&scope=snsapi_userinfo&state=5f582dd3683c2e0ae3aaacee-noguard-https://api.moeshin.com/univs_ssxx_uid/result.php/&connect_redirect=1#wechat_redirect  
#### 1.可参考GUI文件内，[@zhanghua000](http:\/\/github.com\/zhanghua000)推荐的方  
#### 2.也可在电脑登录最新版微信，将答题页面分享给文件助手，电脑打开该页面并登录，使用抓包软件获取请求header里的token
#### 3. 扫描二维码获取uid, 根据uid获得token (3.24更新)

#### 获得token，将以下链接中的xxxx改为自己的uid    
https://ssxx.univs.cn/cgi-bin/authorize/token/?uid=xxxx&tdsourcetag=s_pctim_aiomsg    
运行main.exe输入token即可开始刷题


### 📧 联系邮箱
#### xiaobaiyeaidaima@gmail.com
## 若对您有所帮助，记得点个Star🌟！！！  
