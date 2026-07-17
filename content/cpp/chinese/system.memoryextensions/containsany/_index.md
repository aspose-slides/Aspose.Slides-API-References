---
title: ContainsAny()
second_title: Aspose.Slides for C++ API 参考
description: 检查只读 span 是否包含任意两个值。
type: docs
weight: 53
url: /zh/system.memoryextensions/containsany/
---
## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) 函数

检查只读 span 是否包含任意两个值。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜索的 span |
| value0 | const T\& | 要搜索的第一个值 |
| value1 | const T\& | 要搜索的第二个值 |

### 返回值

如果在 span 中找到任意一个值则返回 true，否则返回 false

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) 函数

检查只读 span 是否包含任意三个值。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜索的 span |
| value0 | const T\& | 要搜索的第一个值 |
| value1 | const T\& | 要搜索的第二个值 |
| value2 | const T\& | 要搜索的第三个值 |

### 返回值

如果在 span 中找到任意一个值则返回 true，否则返回 false

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&) 函数

检查可变 span 是否包含任意两个值。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜索的可变 span |
| value0 | const T\& | 要搜索的第一个值 |
| value1 | const T\& | 要搜索的第二个值 |

### 返回值

如果在 span 中找到任意一个值则返回 true，否则返回 false

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&, const T\&) 函数

检查可变 span 是否包含任意三个值。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜索的可变 span |
| value0 | const T\& | 要搜索的第一个值 |
| value1 | const T\& | 要搜索的第二个值 |
| value2 | const T\& | 要搜索的第三个值 |

### 返回值

如果在 span 中找到任意一个值则返回 true，否则返回 false

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 函数

检查只读 span 是否包含另一个 span 中的任意值。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | spans 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜索的 span |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜索的值 span |

### 返回值

如果在 span 中找到 values 中的任意一个值则返回 true，否则返回 false

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 函数

检查可变 span 是否包含只读 span 中的任意值。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | spans 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜索的可变 span |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜索的只读值 span |

### 返回值

如果在 span 中找到 values 中的任意一个值则返回 true，否则返回 false

## 参见

* 类 [ReadOnlySpan](../../system/readonlyspan/)
* 类 [Span](../../system/span/)
* 命名空间 [System::MemoryExtensions](../)
* 库 [Aspose.Slides](../../)