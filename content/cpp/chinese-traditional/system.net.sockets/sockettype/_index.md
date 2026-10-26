---
title: SocketType
second_title: Aspose.Slides for C++ API 參考文件
description: 列舉套接字類型。
type: docs
weight: 131
url: /zh-hant/system.net.sockets/sockettype/
---
## SocketType 列舉

列舉套接字類型。

```cpp
enum class SocketType
```

### 值

| 名稱 | 值 | 說明 |
| --- | --- | --- |
| Stream | 1 | 支援可靠的雙向、基於連線的位元組串流，且不會重複資料，亦不保留邊界。 |
| Dgram | 2 | 支援資料報文，這些是無連線、不可靠且具有固定最大長度的訊息。 |
| Raw | 3 | 支援存取底層傳輸協定。 |
| Rdm | 4 | 支援無連線、以訊息為導向、可靠傳遞的訊息，且在資料中保留訊息邊界。 |
| Seqpacket | 5 | 提供面向連線且可靠的雙向有序位元組串流在網路上的傳輸。 |
| Unknown | n/a | 未知的類型。 |

## 另請參閱

* 命名空間 [System::Net::Sockets](../)
* 程式庫 [Aspose.Slides](../../)