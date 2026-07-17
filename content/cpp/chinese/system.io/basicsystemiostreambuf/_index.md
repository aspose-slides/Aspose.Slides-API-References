---
title: BasicSystemIOStreamBuf
second_title: Aspose.Slides C++ API 参考
description: "表示一个缓冲区，用于包装 System::IO::Stream 类似的流，并允许它们作为类似 std::iostream 的内部缓冲区使用。"
type: docs
weight: 40
url: /zh/system.io/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf 类

表示一个缓冲区，用于包装 [System::IO::Stream](../stream/) 类似的流，并允许它们作为类似 std::iostream 流的内部缓冲区使用。

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamBuf : public std::basic_streambuf<Elem, std::char_traits<Elem>>
```

## 方法

| 方法 | 描述 |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamBuf](./)\&&) | 在移动构造函数和移动赋值运算符中使用，以重置指针并调用 [swap()](./swap/)。 |
| explicit [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)() | 构造一个新的 [BasicSystemIOStreamBuf](./) 实例。 |
| explicit [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/), const std::locale\&) | 构造一个新的 [BasicSystemIOStreamBuf](./) 实例。 |
| [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [BasicSystemIOStreamBuf](./)\&) | 复制构造函数。已删除。 |
| [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)([BasicSystemIOStreamBuf](./)\&&) | 移动构造函数。 |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamBuf](./)\&) | 复制赋值运算符。已删除。 |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamBuf](./)\&&) | 移动赋值运算符。 |
| void [swap](./swap/)([BasicSystemIOStreamBuf](./)\&) | 在 *this 和 right 不相等时调用 swap。 |
| [~BasicSystemIOStreamBuf](./~basicsystemiostreambuf/)() override | 析构函数。 |

## 类型别名

| 类型别名 | 描述 |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mysb](./mysb/) |  |
| [int_type](./int_type/) |  |
| [pos_type](./pos_type/) |  |
| [off_type](./off_type/) |  |

## 另请参见

* 命名空间 [System::IO](../)
* 库 [Aspose.Slides](../../)