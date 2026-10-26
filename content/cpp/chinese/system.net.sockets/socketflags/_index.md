---
title: SocketFlags
second_title: Aspose.Slides C++ API 参考
description: 提供套接字消息的常量值。
type: docs
weight: 222
url: /zh/system.net.sockets/socketflags/
---
## SocketFlags 枚举

提供套接字消息的常量值。

```cpp
enum class SocketFlags
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | 0 | 此调用未使用任何标志。 |
| OutOfBand | 1 | 正在处理带外数据。 |
| Peek | 2 | 窥视传入的消息。 |
| DontRoute | 4 | 在不使用路由表的情况下发送消息。 |
| Truncated | 256 | 消息太大，无法装入指定的缓冲区，已被截断。 |
| ControlDataTruncated | 512 | 控制数据大于64 KB，且无法装入内部缓冲区，已被截断。 |
| Broadcast | 1024 | 广播数据包。 |
| Multicast | 2048 | 多播数据包。 |
| Partial | 32768 | 部分发送或接收的消息。 |

## 另请参阅

* 命名空间 [System::Net::Sockets](../)
* 库 [Aspose.Slides](../../)