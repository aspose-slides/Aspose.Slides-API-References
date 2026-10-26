---
title: Replace()
second_title: Aspose.Slides for C++ API 参考
description: 在 Span 中将某个值的所有出现替换为新值。
type: docs
weight: 287
url: /zh/system.memoryextensions/replace/
---
## System::MemoryExtensions::Replace(Span\<T\>\&, const T\&, const T\&) 函数

在 [Span](../../system/span/) 中将值的所有出现替换为新值。

```cpp
template<typename T> void System::MemoryExtensions::Replace(Span<T> &span, const T &oldValue, const T &newValue)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | 要就地修改的 span |
| oldValue | const T\& | 要搜索并替换的值 |
| newValue | const T\& | 用于替换 oldValue 的新值 |

## System::MemoryExtensions::Replace(const ReadOnlySpan\<T\>\&, Span\<T\>\&, const T\&, const T\&) 函数

将元素从 source 复制到 destination，在复制过程中替换指定的值。

```cpp
template<typename T> void System::MemoryExtensions::Replace(const ReadOnlySpan<T> &source, Span<T> &destination, const T &oldValue, const T &newValue)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | spans 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要复制的 source [ReadOnlySpan](../../system/readonlyspan/) |
| destination | [Span](../../system/span/)\<T\>\& | 要复制到的 destination [Span](../../system/span/) |
| oldValue | const T\& | 在复制期间要搜索并替换的值 |
| newValue | const T\& | 用于替换 oldValue 的新值 |

## 另见

* 类 [Span](../../system/span/)
* 类 [ReadOnlySpan](../../system/readonlyspan/)
* 命名空间 [System::MemoryExtensions](../)
* 库 [Aspose.Slides](../../)