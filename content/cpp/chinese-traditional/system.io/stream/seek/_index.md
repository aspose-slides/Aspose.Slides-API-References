---
title: Seek()
second_title: Aspose.Slides for C++ API 參考
description: 設定目前物件所代表的串流之位置。
type: docs
weight: 79
url: /zh-hant/system.io/stream/seek/
---
## Stream::Seek(int64_t, SeekOrigin) 方法

設定目前物件所代表的串流之位置。

```cpp
virtual int64_t System::IO::Stream::Seek(int64_t offset, SeekOrigin origin)=0
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| offset | **int64_t** | 相對於 **origin** 指定的位置的位元組偏移量 |
| origin | [SeekOrigin](../../seekorigin/) | 指定計算偏移量的起始位置以及方向 |

### 返回值

串流的新位置

## 另見

* 列舉 [SeekOrigin](../../seekorigin/)
* 類別 [Stream](../)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)