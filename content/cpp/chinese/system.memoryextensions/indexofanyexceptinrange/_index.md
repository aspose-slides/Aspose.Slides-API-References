---
title: IndexOfAnyExceptInRange()
second_title: Aspose.Slides for C++ API 参考
description: 在 ReadOnlySpan<T> 中查找第一个超出指定范围的元素的索引
type: docs
weight: 183
url: /zh/system.memoryextensions/indexofanyexceptinrange/
---
## System::MemoryExtensions::IndexOfAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) 函数

在 ReadOnlySpan<T> 中查找第一个超出指定范围的元素的索引

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 跨度中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜索的跨度 |
| lowInclusive | const T\& | 范围的下界（含） |
| highInclusive | const T\& | 范围的上界（含） |

### 返回值

范围外的第一个元素的零基索引，如果未找到则返回 -1

## System::MemoryExtensions::IndexOfAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) 函数

在 Span<T> 中查找第一个超出指定范围的元素的索引

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 跨度中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜索的跨度 |
| lowInclusive | const T\& | 范围的下界（含） |
| highInclusive | const T\& | 范围的上界（含） |

### 返回值

范围外的第一个元素的零基索引，如果未找到则返回 -1

## 另请参见

* 类 [ReadOnlySpan](../../system/readonlyspan/)
* 类 [Span](../../system/span/)
* 命名空间 [System::MemoryExtensions](../)
* 库 [Aspose.Slides](../../)