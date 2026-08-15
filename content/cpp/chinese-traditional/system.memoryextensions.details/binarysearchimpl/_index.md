---
title: BinarySearchImpl()
second_title: Aspose.Slides for C++ API 參考
description: 通用二元搜尋實作。
type: docs
weight: 118
url: /zh-hant/system.memoryextensions.details/binarysearchimpl/
---
## System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan\<T\>\&, const TValue\&, TCompareFunc) 函式

通用二元搜尋實作。

```cpp
template<typename T,typename TValue,typename TCompareFunc> int32_t System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan<T> &span, const TValue &value, TCompareFunc compareFunc)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | span 中元素的型別 |
| TValue | 要搜尋之值的型別 |
| TCompareFunc | 比較用的函式型別 |

### 引數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜尋的 span |
| value | const TValue\& | 要搜尋的值 |
| compareFunc | TCompareFunc | 比較值與 span 元素並傳回 **int32_t** (-1, 0, 1) 的函式 |

### 傳回值

[Index](../../system/index/) 為找到的元素或插入點的位元補碼

## 參閱

* 類別 [ReadOnlySpan](../../system/readonlyspan/)
* 命名空間 [System::MemoryExtensions::Details](../)
* 函式庫 [Aspose.Slides](../../)