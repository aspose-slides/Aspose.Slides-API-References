---
title: Seek()
second_title: Aspose.Slides for C++ API 參考文件
description: 設定目前物件所代表的串流之位置。
type: docs
weight: 105
url: /zh-hant/system.io/memorystream/seek/
---
## MemoryStream::Seek(int64_t, SeekOrigin) 方法

設定目前物件所代表的串流之位置。

```cpp
int64_t System::IO::MemoryStream::Seek(int64_t offset, SeekOrigin origin) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| offset | **int64_t** | 相對於 **origin** 指定之位置的位元組偏移量 |
| origin | [SeekOrigin](../../seekorigin/) | 指定計算偏移量的起始位置及方向 |

### 返回值

串流的新位置

## 另見

* 列舉 [SeekOrigin](../../seekorigin/)
* 類別 [MemoryStream](../)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)