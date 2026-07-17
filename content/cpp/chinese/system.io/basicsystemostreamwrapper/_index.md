---
title: BasicSystemOStreamWrapper
second_title: Aspose.Slides for C++ API 参考
description: "表示一个类似 std::ostream 的包装器，使用 BasicSystemIOStreamBuf 作为内部缓冲区。"
type: docs
weight: 79
url: /zh/system.io/basicsystemostreamwrapper/
---
## BasicSystemOStreamWrapper 类

表示一个类似 std::ostream 的包装器，使用 [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) 作为内部缓冲区。

```cpp
template<typename Elem,typename Traits>class BasicSystemOStreamWrapper : public std::basic_ostream<Elem, std::char_traits<Elem>>
```

## 方法

| 方法 | 描述 |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemOStreamWrapper](./)\&&) | 用于在移动构造函数和移动赋值运算符中重置指针并调用 [swap()](./swap/)。 |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | 构造 [BasicSystemOStreamWrapper](./) 的新实例。 |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)(const [BasicSystemOStreamWrapper](./)\&) | 拷贝构造函数。已删除。 |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([BasicSystemOStreamWrapper](./)\&&) | 移动构造函数。 |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemOStreamWrapper](./)\&) | 拷贝赋值运算符。已删除。 |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemOStreamWrapper](./)\&&) | 移动赋值运算符。 |
| void [swap](./swap/)([BasicSystemOStreamWrapper](./)\&) | 调用 swap *this 和 **right**，如果它们不相等。 |

## 类型别名

| 类型别名 | 描述 |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |

## 另见

* 命名空间 [System::IO](../)
* 库 [Aspose.Slides](../../)