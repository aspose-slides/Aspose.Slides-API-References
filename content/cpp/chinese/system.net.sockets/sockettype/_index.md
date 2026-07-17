---
title: SocketType
second_title: Aspose.Slides for C++ API 参考
description: 枚举套接字类型。
type: docs
weight: 131
url: /zh/system.net.sockets/sockettype/
---
## SocketType 枚举

枚举套接字类型。

```cpp
enum class SocketType
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Stream | 1 | 支持可靠、双向、基于连接的字节流，且不重复数据，也不保留边界的类型。 |
| Dgram | 2 | 支持数据报的类型，数据报是无连接、不可靠的固定最大长度消息。 |
| Raw | 3 | 支持访问底层传输协议的类型。 |
| Rdm | 4 | 支持无连接、面向消息、可靠传递的消息，并在数据中保留消息边界的类型。 |
| Seqpacket | 5 | 提供面向连接且可靠的双向有序字节流在网络间传输的类型。 |
| Unknown | n/a | 未知类型。 |

## 另请参见

* 命名空间 [System::Net::Sockets](../)
* 库 [Aspose.Slides](../../)