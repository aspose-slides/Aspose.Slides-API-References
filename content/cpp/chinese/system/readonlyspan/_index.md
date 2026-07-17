---
title: ReadOnlySpan
second_title: Aspose.Slides C++ API 参考
description: 用于在 Span 类中使用。
type: docs
weight: 1184
url: /zh/system/readonlyspan/
---
## ReadOnlySpan 类

用于在 [Span](../span/) 类中使用。

```cpp
template<typename T>class ReadOnlySpan : public System::Details::SpanCore<const T, ReadOnlySpan<T>, Span<T>>
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型。此类提供了一种类型安全的方式，以只读方式处理对象的连续序列。它可用于包装数组、栈数组或原始指针，同时保持边界检查。[ReadOnlySpan](./) 不拥有其指向的内存——它只是对现有内存的视图。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [ReadOnlySpan](./readonlyspan/)(const [Span](../span/)\<T\>\&) | 从常规 span 构造只读 span。 |
| static [ThisType](./) [to_ReadOnlySpan](./to_readonlyspan/)(const typename BaseType::ArrayPtrT\&) | 将数组转换为 [ReadOnlySpan](./)。 |

## 备注

表示任意内存的只读连续区域。

## 另见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)