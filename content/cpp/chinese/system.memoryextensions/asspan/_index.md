---
title: AsSpan()
second_title: Aspose.Slides C++ API 参考
description: 从数组创建一个跨度。
type: docs
weight: 1
url: /zh/system.memoryextensions/asspan/
---
## System::MemoryExtensions::AsSpan(const ArrayPtr\<T\>\&, int32_t, int32_t) 函数

从数组创建一个跨度。

```cpp
template<typename T> Span<T> System::MemoryExtensions::AsSpan(const ArrayPtr<T> &array, int32_t start=0, int32_t length=-1)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 数组中元素的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | 源数组。 |
| start | **int32_t** | 数组中的起始索引。 |
| length | **int32_t** | 跨度的长度。 |

### 返回值

Span<T>，跨越数组的指定部分。

## System::MemoryExtensions::AsSpan(const String\&, int32_t, int32_t) 函数

从字符串创建一个只读跨度。

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::AsSpan(const String &text, int32_t start=0, int32_t length=-1)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | const [String](../../system/string/)\& | 源字符串。 |
| start | **int32_t** | 字符串中的起始索引。 |
| length | **int32_t** | 跨度的长度。 |

### 返回值

ReadOnlySpan<char16_t>，跨越字符串的指定部分。

## 另请参阅

* 类型定义 [ArrayPtr](../../system/arrayptr/)
* 类 [Span](../../system/span/)
* 类 [ReadOnlySpan](../../system/readonlyspan/)
* 类 [String](../../system/string/)
* 命名空间 [System::MemoryExtensions](../)
* 库 [Aspose.Slides](../../)