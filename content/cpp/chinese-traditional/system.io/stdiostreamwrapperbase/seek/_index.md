---
title: Seek()
second_title: Aspose.Slides for C++ API 參考文件
description: 設定由目前物件所表示的串流位置。
type: docs
weight: 40
url: /zh-hant/system.io/stdiostreamwrapperbase/seek/
---
## STDIOStreamWrapperBase::Seek(int64_t, SeekOrigin) 方法


設定由目前物件所表示的串流位置。

```cpp
virtual int64_t System::IO::STDIOStreamWrapperBase<T, typename>::Seek(int64_t offset, SeekOrigin origin) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| offset | **int64_t** | 相對於 **origin** 所指定位置的位元組偏移量 |
| origin | [SeekOrigin](../../seekorigin/) | 指定計算偏移量的起始位置以及方向 |

### 返回值

串流的新位置

## 參見

* 列舉 [SeekOrigin](../../seekorigin/)
* 類別 [STDIOStreamWrapperBase](../)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)