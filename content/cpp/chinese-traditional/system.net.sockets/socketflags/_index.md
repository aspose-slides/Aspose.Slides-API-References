---
title: SocketFlags
second_title: Aspose.Slides for C++ API 參考
description: 提供有關 socket 訊息的常數值。
type: docs
weight: 222
url: /zh-hant/system.net.sockets/socketflags/
---
## SocketFlags 列舉

提供有關 socket 訊息的常數值。

```cpp
enum class SocketFlags
```

### 值

| 名稱 | 值 | 描述 |
| --- | --- | --- |
| None | 0 | 此呼叫未使用任何旗標。 |
| OutOfBand | 1 | 正在處理帶外資料。 |
| Peek | 2 | 窺視傳入訊息。 |
| DontRoute | 4 | 在不使用路由表的情況下傳送訊息。 |
| Truncated | 256 | 訊息太大，無法放入指定的緩衝區，已被截斷。 |
| ControlDataTruncated | 512 | 控制資料大於 64 KB，無法放入內部緩衝區，已被截斷。 |
| Broadcast | 1024 | 廣播封包。 |
| Multicast | 2048 | 多播封包。 |
| Partial | 32768 | 訊息部分傳送或接收。 |

## 另見

* 命名空間 [System::Net::Sockets](../)
* 函式庫 [Aspose.Slides](../../)