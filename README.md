# bilibiliLuckyDraw

你B抽奖

就简简单单想抽个奖发个福利，为什么一定要电磁力呢……所以就闲下来写了个简单脚本。

顺手写了直播用的灭霸抽奖，更紧张更刺激。

勉勉强强也支持了560个转发以后的抽奖，但是必须隔大约500个转发以内就要准备抽奖一下。脚本会把转发用户的信息都记录到本地，到最后可以合并起来进行抽奖。

---

## 如何安装

很简单，先安装Greasemonkey/Tampermonkey等用户脚本程序，然后直接点开bilibiliLuckyDraw.user.js，再点一下右上角的RAW按钮，你的浏览器就会提示你安装了。

---

## 如何使用

更简单了，点进想要抽奖的动态，然后点左下角准备抽奖，准备完成以后就可以进行快速/灭霸抽奖了。560+转发的抽奖请隔大约500次转发就准备抽奖一下，防止遗漏。正式开奖前如果想要限定粉丝的话，建议先同步下粉丝。同步粉丝请务必确定登录的账户无误。

保存、载入、清除存档是用来把本地保存的数据迁移到别的电脑上用的，这样你就可以使用不同的电脑来抽那些转发大于560的动态了。导入数据请在点击准备抽奖更新转发列表之前，导入数据会强制覆盖掉本地所有的数据的。

---

## 特别：iOS上的使用

iOS有部分浏览器也是支持的，比如Alook（其他浏览器可以参考Alook类似的方法，具体参照软件说明）。在Alook上，你可以把bilibiliLuckyDraw.user.js的所有内容先复制下来，然后打开Alook的 设置->自定义设置->JavaScript扩展，然后点击右上角的+，新建一个被动扩展。名称随意写，匹配类型为域名，匹配值填写t.bilibili.com。运行时间保持默认即可，最后在JavaScript代码里粘贴复制下来的代码，存储就可以了。注意：iOS可能不支持存档的导出功能，目前不清楚是浏览器限制还是别的什么，之后会看看的。
