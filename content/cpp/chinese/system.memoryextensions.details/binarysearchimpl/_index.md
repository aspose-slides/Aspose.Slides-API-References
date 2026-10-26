---
title: BinarySearchImpl()
second_title: Aspose.Slides for C++ API 参考
description: 常规二分查找实现。
type: docs
weight: 118
url: /zh/system.memoryextensions.details/binarysearchimpl/
---
## System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan\<T\>\&, const TValue\&, TCompareFunc) function

常规二分查找实现。

```cpp
template<typename T,typename TValue,typename TCompareFunc> int32_t System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan<T> &span, const TValue &value, TCompareFunc compareFunc)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |
| TValue | 要搜索的值的类型 |
| TCompareFunc | 比较函数的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜索的 span |
| value | const TValue\& | 要搜索的值 |
| compareFunc | TCompareFunc | 比较值与 span 元素并返回 **int32_t**（-1、0、1）的函数 |

### 返回值

找到的元素的索引或插入位置的按位取反

## 另见

* 类 [ReadOnlySpan](../../system/readonlyspan/)
* 命名空间 [System::MemoryExtensions::Details](../)
* 库 [Aspose.Slides](../../)