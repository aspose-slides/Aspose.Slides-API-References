---
title: BasicSystemIOStreamWrapper
second_title: Aspose.Slides for C++ API 参考
description: "表示一个类似 std::iostream 的包装器，使用 BasicSystemIOStreamBuf 作为内部缓冲区。"
type: docs
weight: 53
url: /zh/system.io/basicsystemiostreamwrapper/
---
## BasicSystemIOStreamWrapper 类

代表一个类似 std::iostream 的包装器，使用 [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) 作为内部缓冲区。

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamWrapper : public std::basic_iostream<Elem, std::char_traits<Elem>>
```

## 方法

| 方法 | 描述 |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamWrapper](./)\&&) | 在移动构造函数和移动赋值运算符中使用，以重置指针并调用 [swap()](./swap/)。 |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | 构造 [BasicSystemIOStreamWrapper](./) 的新实例。 |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)(const [BasicSystemIOStreamWrapper](./)\&) | 拷贝构造函数。已删除。 |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([BasicSystemIOStreamWrapper](./)\&&) | 移动构造函数。 |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamWrapper](./)\&) | 拷贝赋值运算符。已删除。 |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamWrapper](./)\&&) | 移动赋值运算符。 |
| void [swap](./swap/)([BasicSystemIOStreamWrapper](./)\&) | 如果它们不相等，则调用交换 *this* 和 **right**。 |

## 类型定义

| 类型定义 | 描述 |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |

## 另请参见

* 命名空间 [System::IO](../)
* 库 [Aspose.Slides](../../)