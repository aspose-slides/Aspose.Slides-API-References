---
title: Seek()
second_title: Aspose.Slides for C++ API 參考
description: 設定由目前物件所代表的串流位置。
type: docs
weight: 79
url: /zh-hant/system.io/binarywriter/seek/
---
## BinaryWriter::Seek(int, System::IO::SeekOrigin) 方法

設定目前物件所表示之串流的位置。

```cpp
int64_t System::IO::BinaryWriter::Seek(int offset, System::IO::SeekOrigin origin=System::IO::SeekOrigin::Begin)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| offset | int | 相對於 **origin** 所指定位置的位元組偏移 |
| origin | [System::IO::SeekOrigin](../../seekorigin/) | 指定計算偏移量的起始位置及其方向 |

### 回傳值

串流的新位置

## 另請參閱

* 列舉 [SeekOrigin](../../seekorigin/)
* 類別 [BinaryWriter](../)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)