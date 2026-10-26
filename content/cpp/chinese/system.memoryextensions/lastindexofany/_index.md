---
title: LastIndexOfAny()
second_title: Aspose.Slides C++ API 参考
description: 在 span 中查找任意三个指定值的最后一次出现。
type: docs
weight: 222
url: /zh/system.memoryextensions/lastindexofany/
---
## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) function

在 span 中查找任意三个指定值的最后一次出现。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
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

最后一次出现的零基索引，如果未找到则返回 -1

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const T\&, const T\&, const T\&) function

在可变 span 中查找任意三个指定值的最后一次出现。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜索的 span |
| value0 | const T\& | 要搜索的第一个值 |
| value1 | const T\& | 要搜索的第二个值 |
| value2 | const T\& | 要搜索的第三个值 |

### 返回值

最后一次出现的零基索引，如果未找到则返回 -1

## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

在 span 中查找任意两个指定值的最后一次出现。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
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

最后一次出现的零基索引，如果未找到则返回 -1

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const T\&, const T\&) function

在可变 span 中查找任意两个指定值的最后一次出现。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const T &value0, const T &value1)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜索的 span |
| value0 | const T\& | 要搜索的第一个值 |
| value1 | const T\& | 要搜索的第二个值 |

### 返回值

最后一次出现的零基索引，如果未找到则返回 -1

## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

在 span 中查找序列中任意值的最后一次出现。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜索的 span |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜索的值序列 |

### 返回值

最后一次出现的零基索引，如果未找到则返回 -1

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

在可变 span 中查找序列中任意值的最后一次出现。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜索的 span |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜索的值序列 |

### 返回值

最后一次出现的零基索引，如果未找到则返回 -1

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const Span\<T\>\&) function

在可变 span 中查找可变序列中任意值的最后一次出现。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const Span<T> &values)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜索的 span |
| values | const [Span](../../system/span/)\<T\>\& | 要搜索的值序列 |

### 返回值

最后一次出现的零基索引，如果未找到则返回 -1

## 另见

* 类 [ReadOnlySpan](../../system/readonlyspan/)
* 类 [Span](../../system/span/)
* 命名空间 [System::MemoryExtensions](../)
* 库 [Aspose.Slides](../../)