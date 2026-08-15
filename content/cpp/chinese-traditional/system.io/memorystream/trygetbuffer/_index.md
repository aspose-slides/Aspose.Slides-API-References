---
title: TryGetBuffer()
second_title: Aspose.Slides for C++ API 參考文件
description: 傳回建立此串流時所使用的無符號位元組陣列。
type: docs
weight: 170
url: /zh-hant/system.io/memorystream/trygetbuffer/
---
## MemoryStream::TryGetBuffer(ArraySegment\<uint8_t\>\&) 方法

返回建立此串流時使用的無符號位元組陣列。

```cpp
bool System::IO::MemoryStream::TryGetBuffer(ArraySegment<uint8_t> &buffer)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | [ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\& | 位元組陣列 - 輸出參數。當此方法返回 true 時，為建立此串流時使用的位元組陣列區段；當此方法返回 false 時，該參數設為預設值。 |

### 傳回值

若轉換成功則為 true。

## 參見

* 類別 [ArraySegment](../../../system/arraysegment/)
* 類別 [MemoryStream](../)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)