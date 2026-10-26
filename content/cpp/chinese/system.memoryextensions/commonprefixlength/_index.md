---
title: CommonPrefixLength()
second_title: Aspose.Slides for C++ API 参考
description: 查找两个 Span 之间公共前缀的长度。
type: docs
weight: 27
url: /zh/system.memoryextensions/commonprefixlength/
---
## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 函数

查找两个 Span 之间公共前缀的长度。

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | Span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 第一个 Span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 第二个 Span |

### 返回值

两个 Span 开始处匹配元素的数量

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 函数

查找可变 Span 与只读 Span 之间公共前缀的长度。

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | Span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 可变 Span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 只读 Span |

### 返回值

两个 Span 开始处匹配元素的数量

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&) 函数

查找两个可变 Span 之间公共前缀的长度。

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | Span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 第一个可变 Span |
| other | const [Span](../../system/span/)\<T\>\& | 第二个可变 Span |

### 返回值

两个 Span 开始处匹配元素的数量

## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) 函数

使用自定义相等比较器查找两个 Span 之间公共前缀的长度。

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | Span 中元素的类型 |
| TEqualityComparer | 相等比较器的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 第一个 Span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 第二个 Span |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | 用于元素比较的相等比较器 |

### 返回值

两个 Span 开始处匹配元素的数量

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) 函数

使用自定义相等比较器查找可变 Span 与只读 Span 之间公共前缀的长度。

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | Span 中元素的类型 |
| TEqualityComparer | 相等比较器的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 可变 Span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 只读 Span |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | 用于元素比较的相等比较器 |

### 返回值

两个 Span 开始处匹配元素的数量

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) 函数

使用自定义相等比较器查找两个可变 Span 之间公共前缀的长度。

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | Span 中元素的类型 |
| TEqualityComparer | 相等比较器的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 第一个可变 Span |
| other | const [Span](../../system/span/)\<T\>\& | 第二个可变 Span |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | 用于元素比较的相等比较器 |

### 返回值

两个 Span 开始处匹配元素的数量

## 另请参见

* 类型定义 [SharedPtr](../../system/sharedptr/)
* 类 [ReadOnlySpan](../../system/readonlyspan/)
* 类 [Span](../../system/span/)
* 命名空间 [System::MemoryExtensions](../)
* 库 [Aspose.Slides](../../)