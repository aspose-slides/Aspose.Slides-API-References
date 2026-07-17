---
title: IndexOfAnyExcept()
second_title: Aspose.Slides for C++ API 参考
description: 在 ReadOnlySpan<T> 中查找第一个不等于指定值的元素的索引
type: docs
weight: 170
url: /zh/system.memoryextensions/indexofanyexcept/
---
## System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) 函数


在 ReadOnlySpan<T> 中查找第一个不等于指定值的元素的索引

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜索的 span |
| value | const T\& | 要从搜索中排除的值 |

### 返回值

第一个不匹配元素的零基索引，如果未找到则返回 -1

## System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) 函数


在 ReadOnlySpan<T> 中查找第一个不等于任意两个指定值的元素的索引

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜索的 span |
| value0 | const T\& | 要从搜索中排除的第一个值 |
| value1 | const T\& | 要从搜索中排除的第二个值 |

### 返回值

第一个不匹配元素的零基索引，如果未找到则返回 -1

## System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) 函数


在 ReadOnlySpan<T> 中查找第一个不等于任意三个指定值的元素的索引

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜索的 span |
| value0 | const T\& | 要从搜索中排除的第一个值 |
| value1 | const T\& | 要从搜索中排除的第二个值 |
| value2 | const T\& | 要从搜索中排除的第三个值 |

### 返回值

第一个不匹配元素的零基索引，如果未找到则返回 -1

## System::MemoryExtensions::IndexOfAnyExcept(const Span\<T\>\&, const T\&) 函数


在 Span<T> 中查找第一个不等于指定值的元素的索引

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const Span<T> &span, const T &value)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜索的 span |
| value | const T\& | 要从搜索中排除的值 |

### 返回值

第一个不匹配元素的零基索引，如果未找到则返回 -1

## System::MemoryExtensions::IndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&) 函数


在 Span<T> 中查找第一个不等于任意两个指定值的元素的索引

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜索的 span |
| value0 | const T\& | 要从搜索中排除的第一个值 |
| value1 | const T\& | 要从搜索中排除的第二个值 |

### 返回值

第一个不匹配元素的零基索引，如果未找到则返回 -1

## System::MemoryExtensions::IndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) 函数


在 Span<T> 中查找第一个不等于任意三个指定值的元素的索引

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜索的 span |
| value0 | const T\& | 要从搜索中排除的第一个值 |
| value1 | const T\& | 要从搜索中排除的第二个值 |
| value2 | const T\& | 要从搜索中排除的第三个值 |

### 返回值

第一个不匹配元素的零基索引，如果未找到则返回 -1

## System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 函数


在一个值的 span 中查找第一个不等于任意值的元素的索引。

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 各 span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜索的 span |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 包含要从搜索中排除的值的 span |

### 返回值

第一个不匹配元素的零基索引，如果未找到则返回 -1

## System::MemoryExtensions::IndexOfAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 函数


在 Span<T> 中查找第一个不等于任意值的元素的索引。

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 各 span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜索的 span |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 包含要从搜索中排除的值的 span |

### 返回值

第一个不匹配元素的零基索引，如果未找到则返回 -1

## 另见

* 类 [ReadOnlySpan](../../system/readonlyspan/)
* 类 [Span](../../system/span/)
* 命名空间 [System::MemoryExtensions](../)
* 库 [Aspose.Slides](../../)