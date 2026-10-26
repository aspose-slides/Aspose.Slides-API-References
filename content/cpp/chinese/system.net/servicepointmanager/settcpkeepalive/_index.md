---
title: SetTcpKeepAlive()
second_title: Aspose.Slides for C++ API 参考
description: 设置指示是否启用 'Keep-Alive' 选项的值。
type: docs
weight: 326
url: /zh/system.net/servicepointmanager/settcpkeepalive/
---
## ServicePointManager::SetTcpKeepAlive(bool, int32_t, int32_t) 方法

设置指示是否启用 'Keep-Alive' 选项的值。

```cpp
static void System::Net::ServicePointManager::SetTcpKeepAlive(bool enabled, int32_t keepAliveTime, int32_t keepAliveInterval)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| enabled | **bool** | 指示 'Keep-Alive' 选项是否已启用的值。 |
| keepAliveTime | **int32_t** | 在首次发送 'Keep-Alive' 包之前的超时时间（毫秒）。 |
| keepAliveInterval | **int32_t** | 发送 'Keep-Alive' 包之间的超时时间（毫秒）。 |

## 另见

* 类 [ServicePointManager](../)
* 命名空间 [System::Net](../../)
* 库 [Aspose.Slides](../../../)