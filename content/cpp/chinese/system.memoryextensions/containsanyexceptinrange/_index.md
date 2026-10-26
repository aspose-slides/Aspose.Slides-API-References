---
title: ContainsAnyExceptInRange()
second_title: Aspose.Slides C++ API 参考
description: 检查只读跨度是否包含超出指定范围的任何元素。
type: docs
weight: 79
url: /zh/system.memoryextensions/containsanyexceptinrange/
---
## System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) 函数

检查只读跨度是否包含超出指定范围的任何元素。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 跨度中元素的类型（必须可比较） |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜索的跨度 |
| lowInclusive | const T\& | 下界（包含） |
| highInclusive | const T\& | 上界（包含） |

### 返回值

如果找到范围外的任何元素则返回 true，否则返回 false

## System::MemoryExtensions::ContainsAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) 函数

检查可变跨度是否包含超出指定范围的任何元素。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 跨度中元素的类型（必须可比较） |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜索的可变跨度 |
| lowInclusive | const T\& | 下界（包含） |
| highInclusive | const T\& | 上界（包含） |

### 返回值

如果找到范围外的任何元素则返回 true，否则返回 false

## 另请参见

* 类 [ReadOnlySpan](../../system/readonlyspan/)
* 类 [Span](../../system/span/)
* 命名空间 [System::MemoryExtensions](../)
* 库 [Aspose.Slides](../../)