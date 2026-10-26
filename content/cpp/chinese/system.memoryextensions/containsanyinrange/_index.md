---
title: ContainsAnyInRange()
second_title: Aspose.Slides C++ API 参考
description: 检查只读 span 是否包含位于指定范围内的任意元素。
type: docs
weight: 92
url: /zh/system.memoryextensions/containsanyinrange/
---
## System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

检查只读 span 是否包含位于指定范围内的任意元素。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型（必须可比较） |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜索的 span |
| lowInclusive | const T\& | 下界（包含） |
| highInclusive | const T\& | 上界（包含） |

### 返回值

如果在范围内找到任何元素则返回 true，否则返回 false

## System::MemoryExtensions::ContainsAnyInRange(const Span\<T\>\&, const T\&, const T\&) function

检查可变 span 是否包含位于指定范围内的任意元素。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型（必须可比较） |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜索的可变 span |
| lowInclusive | const T\& | 下界（包含） |
| highInclusive | const T\& | 上界（包含） |

### 返回值

如果在范围内找到任何元素则返回 true，否则返回 false

## 参考

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)