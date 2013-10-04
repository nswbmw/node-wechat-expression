node-wechat-expression 是微信内置表情的代码包。

在微信聊天中，我们发送的表情其实是发送的代表该表情的一个特殊的字符串，接收方收到这段特殊的字符串后展示相应的表情。这是我在使用 [node-wechat](https://github.com/nswbmw/node-wechat) 的时候，偶然发现 `text` 事件监听器也能收到来自发送的表情信号想到的。

一个简单的例子：在微信中发送 `/::D` 你会发现发送出去的是一个 `呲牙` 的表情。

可以结合  [node-wechat](https://github.com/nswbmw/node-wechat) 或者 [wechat](https://github.com/node-webot/wechat) 一块使用。