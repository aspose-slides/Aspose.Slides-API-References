---
title: Poll()
second_title: Aspose.Slides for C++ API 參考
description: 根據指定的輪詢模式返回 socket 的狀態。
type: docs
weight: 742
url: /zh-hant/system.net.sockets/socket/poll/
---
## Socket::Poll(int32_t, SelectMode) 方法

返回基於指定輪詢模式的 socket 狀態。

```cpp
bool System::Net::Sockets::Socket::Poll(int32_t microSeconds, SelectMode mode)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| microSeconds | **int32_t** | 等待回應的時間（毫秒）。 |
| mode | [SelectMode](../../selectmode/) | 輪詢模式。 |

### 返回值

基於指定輪詢模式的 socket 狀態。

## 參見

* 列舉 [SelectMode](../../selectmode/)
* 類別 [Socket](../)
* 命名空間 [System::Net::Sockets](../../)
* 函式庫 [Aspose.Slides](../../../)