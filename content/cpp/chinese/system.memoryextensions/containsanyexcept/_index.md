---
title: ContainsAnyExcept()
second_title: Aspose.Slides for C++ API 参考
description: 检查只读 span 是否包含除三个指定值之外的任何元素。
type: docs
weight: 66
url: /zh/system.memoryextensions/containsanyexcept/
---
## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) 函数

检查只读 span 是否包含除指定的三个值之外的任何元素。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜索的 span |
| value0 | const T\& | 要排除的第一个值 |
| value1 | const T\& | 要排除的第二个值 |
| value2 | const T\& | 要排除的第三个值 |

### 返回值

如果找到任何与指定值不同的元素则返回 true，否则返回 false

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) 函数

检查可变 span 是否包含除三个指定值之外的任何元素。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜索的可变 span |
| value0 | const T\& | 要排除的第一个值 |
| value1 | const T\& | 要排除的第二个值 |
| value2 | const T\& | 要排除的第三个值 |

### 返回值

如果找到任何与指定值不同的元素则返回 true，否则返回 false

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) 函数

检查只读 span 是否包含除两个指定值之外的任何元素。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜索的 span |
| value0 | const T\& | 要排除的第一个值 |
| value1 | const T\& | 要排除的第二个值 |

### 返回值

如果找到任何与指定值不同的元素则返回 true，否则返回 false

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&) 函数

检查可变 span 是否包含除两个指定值之外的任何元素。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜索的可变 span |
| value0 | const T\& | 要排除的第一个值 |
| value1 | const T\& | 要排除的第二个值 |

### 返回值

如果找到任何与指定值不同的元素则返回 true，否则返回 false

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) 函数

检查只读 span 是否包含除指定值之外的任何元素。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜索的 span |
| value | const T\& | 要排除的值 |

### 返回值

如果找到任何与指定值不同的元素则返回 true，否则返回 false

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&) 函数

检查可变 span 是否包含除指定值之外的任何元素。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜索的可变 span |
| value | const T\& | 要排除的值 |

### 返回值

如果找到任何与指定值不同的元素则返回 true，否则返回 false

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 函数

检查只读 span 是否包含除另一个 span 中的值之外的任何元素。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜索的 span |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要排除的值 span |

### 返回值

如果找到任何不在 values 中的元素则返回 true，否则返回 false

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 函数

检查可变 span 是否包含除只读 span 中的值之外的任何元素。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜索的可变 span |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要排除的只读值 span |

### 返回值

如果找到任何不在 values 中的元素则返回 true，否则返回 false

## 另请参见

* 类 [ReadOnlySpan](../../system/readonlyspan/)
* 类 [Span](../../system/span/)
* 命名空间 [System::MemoryExtensions](../)
* 库 [Aspose.Slides](../../)