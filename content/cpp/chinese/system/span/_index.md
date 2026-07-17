---
title: Span
second_title: Aspose.Slides for C++ API 参考
description: "表示一块任意内存的连续区域，类似于 C++20 的 std::span。"
type: docs
weight: 1236
url: /zh/system/span/
---
## Span 类

表示一块任意内存的连续区域，类似于 C++20 的 std::span。

```cpp
template<typename T>class Span : public System::Details::SpanCore<T, Span<T>, Span<T>>
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型。此类提供一种类型安全的方式来处理对象的连续序列。它可用于包装数组、栈数组或原始指针，同时保持边界检查。[Span](./) 并不拥有其指向的内存——它仅是对现有内存的视图。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| void [Clear](./clear/)() const | 通过将所有元素设置为默认值来清除 span 的内容。 |
| void [Fill](./fill/)(const T\&) const | 使用指定的值填充 span。 |
| static [ThisType](./) [to_Span](./to_span/)(const typename BaseType::ArrayPtrT\&) | 将数组转换为 [Span](./)。 |

## 另见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)