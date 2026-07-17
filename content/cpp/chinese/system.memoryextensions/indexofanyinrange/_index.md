---
title: IndexOfAnyInRange()
second_title: Aspose.Slides for C++ API 参考
description: 在 ReadOnlySpan<T> 中查找位于指定范围的第一个元素的索引
type: docs
weight: 196
url: /zh/system.memoryextensions/indexofanyinrange/
---
## System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) 函数

在 ReadOnlySpan<T> 中查找位于指定范围的第一个元素的索引

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜索的 span |
| lowInclusive | const T\& | 范围的下界（包含） |
| highInclusive | const T\& | 范围的上界（包含） |

### 返回值

范围内第一个元素的零基索引，如果未找到则返回 -1

## System::MemoryExtensions::IndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) 函数

在 Span<T> 中查找位于指定范围的第一个元素的索引

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜索的 span |
| lowInclusive | const T\& | 范围的下界（包含） |
| highInclusive | const T\& | 范围的上界（包含） |

### 返回值

范围内第一个元素的零基索引，如果未找到则返回 -1

## 另见

* 类 [ReadOnlySpan](../../system/readonlyspan/)
* 类 [Span](../../system/span/)
* 命名空间 [System::MemoryExtensions](../)
* 库 [Aspose.Slides](../../)