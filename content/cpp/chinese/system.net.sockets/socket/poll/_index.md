---
title: Poll()
second_title: Aspose.Slides for C++ API 参考
description: 根据指定的轮询模式返回套接字的状态。
type: docs
weight: 742
url: /zh/system.net.sockets/socket/poll/
---
## Socket::Poll(int32_t, SelectMode) 方法

返回基于指定轮询模式的套接字状态。

```cpp
bool System::Net::Sockets::Socket::Poll(int32_t microSeconds, SelectMode mode)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| microSeconds | **int32_t** | 等待响应的时间（毫秒）。 |
| mode | [SelectMode](../../selectmode/) | 轮询模式。 |

### 返回值

基于指定轮询模式的套接字状态。

## 另见

* 枚举 [SelectMode](../../selectmode/)
* 类 [Socket](../)
* 命名空间 [System::Net::Sockets](../../)
* 库 [Aspose.Slides](../../../)