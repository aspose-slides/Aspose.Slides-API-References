---
title: LastIndexOfAnyExcept()
second_title: Aspose.Slides for C++ API 参考
description: 在跨度中查找除三个指定值之外的任何元素的最后一次出现。
type: docs
weight: 235
url: /zh/system.memoryextensions/lastindexofanyexcept/
---
## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) function

在跨度中查找除三个指定值之外的任何元素的最后一次出现。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### 模板参数

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜索的跨度 |
| value0 | const T\& | 要排除的第一个值 |
| value1 | const T\& | 要排除的第二个值 |
| value2 | const T\& | 要排除的第三个值 |

### 返回值

最后一个未被排除的元素的零基索引；如果未找到则返回 -1

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) function

在可变跨度中查找除三个指定值之外的任何元素的最后一次出现。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### 模板参数

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜索的跨度 |
| value0 | const T\& | 要排除的第一个值 |
| value1 | const T\& | 要排除的第二个值 |
| value2 | const T\& | 要排除的第三个值 |

### 返回值

最后一个未被排除的元素的零基索引；如果未找到则返回 -1

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

在跨度中查找除两个指定值之外的任何元素的最后一次出现。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### 模板参数

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜索的跨度 |
| value0 | const T\& | 要排除的第一个值 |
| value1 | const T\& | 要排除的第二个值 |

### 返回值

最后一个未被排除的元素的零基索引；如果未找到则返回 -1

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&) function

在可变跨度中查找除两个指定值之外的任何元素的最后一次出现。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```

### 模板参数

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜索的跨度 |
| value0 | const T\& | 要排除的第一个值 |
| value1 | const T\& | 要排除的第二个值 |

### 返回值

最后一个未被排除的元素的零基索引；如果未找到则返回 -1

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) function

在跨度中查找除指定值之外的任何元素的最后一次出现。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```

### 模板参数

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜索的跨度 |
| value | const T\& | 要排除的值 |

### 返回值

最后一个未被排除的元素的零基索引；如果未找到则返回 -1

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&) function

在可变跨度中查找除指定值之外的任何元素的最后一次出现。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value)
```

### 模板参数

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜索的跨度 |
| value | const T\& | 要排除的值 |

### 返回值

最后一个未被排除的元素的零基索引；如果未找到则返回 -1

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

在跨度中查找除序列中的值之外的任何元素的最后一次出现。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### 模板参数

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜索的跨度 |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要排除的值序列 |

### 返回值

最后一个未被排除的元素的零基索引；如果未找到则返回 -1

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

在可变跨度中查找除序列中的值之外的任何元素的最后一次出现。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### 模板参数

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜索的跨度 |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要排除的值序列 |

### 返回值

最后一个未被排除的元素的零基索引；如果未找到则返回 -1

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const Span\<T\>\&) function

在可变跨度中查找除可变序列中的值之外的任何元素的最后一次出现。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const Span<T> &values)
```

### 模板参数

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜索的跨度 |
| values | const [Span](../../system/span/)\<T\>\& | 要排除的值序列 |

### 返回值

最后一个未被排除的元素的零基索引；如果未找到则返回 -1

## 另请参见

* 类 [ReadOnlySpan](../../system/readonlyspan/)
* 类 [Span](../../system/span/)
* 命名空间 [System::MemoryExtensions](../)
* 库 [Aspose.Slides](../../)