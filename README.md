## duck不必fork！ duck不必fork！duck不必fork！ 给个星星就行

## 免责声明: 

* 本仓库发布的Script项目中涉及的任何解锁和解密分析脚本，仅用于测试和学习研究，不能保证其合法性，准确性，完整性和有效性，请根据情况自行判断.

* shaolin-kongfu对任何脚本问题概不负责，包括但不限于由任何脚本错误导致的任何损失或损害.

* 间接使用脚本的任何用户，包括但不限于建立VPS或在某些行为违反国家/地区法律或相关法规的情况下进行传播, shaolin-kongfu 对于由此引起的任何隐私泄漏或其他后果概不负责.

* 请勿将Script项目的任何内容用于商业或非法目的，否则后果自负.

* 如果任何单位或个人认为该项目的脚本可能涉嫌侵犯其权利，则应及时通知并提供身份证明，所有权证明，我们将在收到认证文件后删除相关脚本.

* 任何以任何方式查看此项目的人或直接或间接使用该Script项目的任何脚本的使用者都应仔细阅读此声明。shaolin-kongfu保留随时更改或补充此免责声明的权利。一旦使用并复制了任何相关脚本或Script项目的规则，则视为您已接受此免责声明.

##### 您必须在下载后的24小时内从计算机或手机中完全删除以上内容.
***您使用或者复制了本仓库且本人制作的任何脚本，则视为`已接受`此免责声明，请仔细阅读***




### 特别感谢：
* [@xl2101200](https://github.com/xl2101200)

* [@Sunert](https://github.com/Sunert)

* [@chavyleung](https://github.com/chavyleung)

# 晶彩天气(v8.3.7)
  
## 重写：  
https://tq.xunsl.com/v17/NewTask/getTaskListByWeather.json  -- 点开福利页即可获取jctqCookie  
https://tq.xunsl.com/v5/CommonReward/toGetReward.json       -- 签到，和福利页任务奖励  
https://tq.xunsl.com/v5/article/info.json                   -- 点开文章获取文章body  
https://tq.xunsl.com/v5/article/detail.json                 -- 点开视频获取视频body  
https://tq.xunsl.com/v5/user/stay.json                      -- 阅读文章或者看视频一段时间后可以获取到时长body  
https://tq.xunsl.com/v5/nameless/adlickstart.json           -- 点开看看赚获取body，可以一直开着，脚本会自动删除重复body  
https://tq.xunsl.com/v5/Weather/giveBoxOnWeather.json       -- 点开福利页浮窗宝箱和观看翻倍视频获取body  
https://tq.xunsl.com/v5/weather/giveTimeInterval.json       -- 点开首页气泡红包和观看翻倍视频获取body  
https://tq.xunsl.com/v5/wechat/withdraw2.json               -- 提现一次对应金额获取body  
https://tq.xunsl.com/v5/CommonReward/toDouble.json          -- 领取签到翻倍奖励后可获取  
  
## 任务：  
jctq_daily.js           -- 领转发页定时宝箱，领福利页定时宝箱，领首页气泡红包，时段转发，刷福利视频，抽奖5次  
jctq_reward.js          -- 签到和翻倍，任务奖励领取，统计今日收益，自动提现  
jctq_kkz.js             -- 完成看看赚任务，删除重复和失效的body  
jctq_read.js            -- 阅读文章，浏览视频  
  
## 分享阅读：  
jctq_shareRead.js       -- 分享和助力阅读，需要在环境变量jctqShareNum里设置要被阅读的次数，不设置默认不跑  

