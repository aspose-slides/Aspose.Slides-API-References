---
title: Seek()
second_title: Aspose.Slides C++ API 參考
description: 設定目前物件所代表的串流位置。
type: docs
weight: 157
url: /zh-hant/system.io/unmanagedmemorystream/seek/
---
## UnmanagedMemoryStream::Seek(int64_t, SeekOrigin) 方法

設定目前物件所代表的串流位置。

```cpp
virtual int64_t System::IO::UnmanagedMemoryStream::Seek(int64_t offset, SeekOrigin loc) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| offset | **int64_t** | 相對於 **origin** 指定位置的位元組位移 |
| loc | [SeekOrigin](../../seekorigin/) | 指定計算位移時的起始位置及其方向 |

### 回傳值

串流的新位置

## 另請參閱

* 列舉 [SeekOrigin](../../seekorigin/)
* 類別 [UnmanagedMemoryStream](../)
* 命名空間 [System::IO](../../)
* 程式庫 [Aspose.Slides](../../../)