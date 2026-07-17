---
title: LastIndexOfAnyExceptInRange()
second_title: Aspose.Slides for C++ API 参考
description: 在跨度中查找超出指定范围的任意元素的最后一次出现。
type: docs
weight: 248
url: /zh/system.memoryextensions/lastindexofanyexceptinrange/
---
## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) 函数

查找跨度中超出指定范围的任何元素的最后一次出现。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜索的跨度 |
| lowInclusive | const T\& | 范围的下界（包含） |
| highInclusive | const T\& | 范围的上界（包含） |

### 返回值

范围外的最后一个元素的零基索引，未找到则返回 -1

## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) 函数

查找可变跨度中超出指定范围的任何元素的最后一次出现。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜索的跨度 |
| lowInclusive | const T\& | 范围的下界（包含） |
| highInclusive | const T\& | 范围的上界（包含） |

### 返回值

范围外的最后一个元素的零基索引，未找到则返回 -1

## 另见

* 类 [ReadOnlySpan](../../system/readonlyspan/)
* 类 [Span](../../system/span/)
* 命名空间 [System::MemoryExtensions](../)
* 库 [Aspose.Slides](../../)