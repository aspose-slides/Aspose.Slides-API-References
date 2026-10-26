---
title: Seek()
second_title: Aspose.Slides for C++ API 參考
description: 設定目前物件所代表的串流位置。
type: docs
weight: 209
url: /zh-hant/system.io/filestream/seek/
---
## FileStream::Seek(int64_t, SeekOrigin) 方法

設定目前物件所代表的串流位置。

```cpp
int64_t System::IO::FileStream::Seek(int64_t offset, SeekOrigin origin) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| offset | **int64_t** | 相對於 **origin** 所指定位置的位元組偏移。 |
| origin | [SeekOrigin](../../seekorigin/) | 指定計算 offset 時的起始位置及方向。 |

### 返回值

串流的新位置。

## 另請參閱

* 列舉 [SeekOrigin](../../seekorigin/)
* 類別 [FileStream](../)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)