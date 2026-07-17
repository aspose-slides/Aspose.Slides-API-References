---
title: IndexOfAny()
second_title: Aspose.Slides C++ API 参考
description: 在 ReadOnlySpan<T> 中查找任意两个指定值的首次出现的索引
type: docs
weight: 157
url: /zh/system.memoryextensions/indexofany/
---
## System::MemoryExtensions::IndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) 函数


在 ReadOnlySpan<T> 中查找任意两个指定值的首次出现的索引

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
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

首次出现的零基索引，如果未找到则为 -1

## System::MemoryExtensions::IndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) 函数


在 ReadOnlySpan<T> 中查找任意三个指定值的首次出现的索引

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
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

首次出现的零基索引，如果未找到则为 -1

## System::MemoryExtensions::IndexOfAny(const Span\<T\>\&, const T\&, const T\&) 函数


在 Span<T> 中查找任意两个指定值的首次出现的索引

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const Span<T> &span, const T &value0, const T &value1)
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

首次出现的零基索引，如果未找到则为 -1

## System::MemoryExtensions::IndexOfAny(const Span\<T\>\&, const T\&, const T\&, const T\&) 函数


在 Span<T> 中查找任意三个指定值的首次出现的索引

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
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

首次出现的零基索引，如果未找到则为 -1

## System::MemoryExtensions::IndexOfAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 函数


在另一个 ReadOnlySpan<T> 中查找来自 span 的任意值的首次出现的索引

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | spans 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜索的 span |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 包含要搜索值的 span |

### 返回值

首次出现的零基索引，如果未找到则为 -1

## System::MemoryExtensions::IndexOfAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 函数


在 Span<T> 中查找来自 span 的任意值的首次出现的索引

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | spans 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜索的 span |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 包含要搜索值的 span |

### 返回值

首次出现的零基索引，如果未找到则为 -1

## 另请参见

* 类 [ReadOnlySpan](../../system/readonlyspan/)
* 类 [Span](../../system/span/)
* 命名空间 [System::MemoryExtensions](../)
* 库 [Aspose.Slides](../../)