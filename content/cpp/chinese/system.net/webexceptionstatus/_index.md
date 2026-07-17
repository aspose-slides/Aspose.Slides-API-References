---
title: WebExceptionStatus
second_title: Aspose.Slides for C++ API 参考
description: 枚举 WebException 类的状态码。
type: docs
weight: 651
url: /zh/system.net/webexceptionstatus/
---
## WebExceptionStatus 枚举

枚举 WebException 类的状态码。

```cpp
enum class WebExceptionStatus
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Success | 0 | 未出现错误。 |
| NameResolutionFailure | 1 | 名称解析服务无法解析主机名。 |
| ConnectFailure | 2 | 无法在传输层联系远程服务点。 |
| ReceiveFailure | 3 | 未从远程服务器收到完整的响应。 |
| SendFailure | 4 | 无法向远程服务器发送完整的请求。 |
| PipelineFailure | 5 | 该请求为流水线请求，但在收到响应之前连接已关闭。 |
| RequestCanceled | 6 | 请求已取消或出现无法分类的错误。 |
| ProtocolError | 7 | 从服务器收到的响应完整，但指示协议级错误。 |
| ConnectionClosed | 8 | 连接被提前关闭。 |
| TrustFailure | 9 | 无法验证服务器证书。 |
| SecureChannelFailure | 10 | 使用 SSL 建立连接时发生错误。 |
| ServerProtocolViolation | 11 | 服务器响应不是有效的 HTTP 响应。 |
| KeepAliveFailure | 12 | 对指定了 “Keep-Alive” 头的请求的连接意外关闭。 |
| Pending | 13 | 内部异步请求待处理。 |
| Timeout | 14 | 在请求的超时间隔内未收到响应。 |
| ProxyNameResolutionFailure | 15 | 名称解析服务无法解析代理主机名。 |
| UnknownError | 16 | 出现未知类型的异常。 |
| MessageLengthLimitExceeded | 17 | 收到超过指定限制的消息。 |
| CacheEntryNotFound | 18 | 未找到指定的缓存条目。 |
| RequestProhibitedByCachePolicy | 19 | 请求未被缓存策略允许。 |
| RequestProhibitedByProxy | 20 | 此请求未被代理允许。 |

## 另见

* 命名空间 [System::Net](../)
* 库 [Aspose.Slides](../../)