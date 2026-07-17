---
title: LastIndexOfAnyInRange()
second_title: Aspose.Slides for C++ API 参考
description: 在 span 中查找指定范围内任意元素的最后一次出现。
type: docs
weight: 261
url: /zh/system.memoryextensions/lastindexofanyinrange/
---
## System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) 函数

查找在 span 中指定范围内任意元素的最后一次出现。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要在其中搜索的 span |
| lowInclusive | const T\& | 范围的下界（包括在内） |
| highInclusive | const T\& | 范围的上界（包括在内） |

### 返回值

范围内最后一个元素的零基索引，如果未找到则返回 -1

## System::MemoryExtensions::LastIndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) 函数

查找在可变 span 中指定范围内任意元素的最后一次出现。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要在其中搜索的 span |
| lowInclusive | const T\& | 范围的下界（包括在内） |
| highInclusive | const T\& | 范围的上界（包括在内） |

### 返回值

范围内最后一个元素的零基索引，如果未找到则返回 -1

## 另见

* 类 [ReadOnlySpan](../../system/readonlyspan/)
* 类 [Span](../../system/span/)
* 命名空间 [System::MemoryExtensions](../)
* 库 [Aspose.Slides](../../)