---
title: BasicSystemIStreamWrapper
second_title: Aspose.Slides C++ API 参考
description: "表示一个类似 std::istream 的包装器，使用 BasicSystemIOStreamBuf 作为内部缓冲区。"
type: docs
weight: 66
url: /zh/system.io/basicsystemistreamwrapper/
---
## BasicSystemIStreamWrapper 类


表示一个类似 std::istream 的包装器，使用 [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) 作为内部缓冲区。

```cpp
template<typename Elem,typename Traits>class BasicSystemIStreamWrapper : public std::basic_istream<Elem, std::char_traits<Elem>>
```

## 方法

| 方法 | 描述 |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIStreamWrapper](./)\&&) | 在移动构造函数和移动赋值运算符中使用，以重置指针并调用 [swap()](./swap/)。 |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | 构造 [BasicSystemIStreamWrapper](./) 的新实例。 |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)(const [BasicSystemIStreamWrapper](./)\&) | 拷贝构造函数。已删除。 |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([BasicSystemIStreamWrapper](./)\&&) | 移动构造函数。 |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIStreamWrapper](./)\&) | 拷贝赋值运算符。已删除。 |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIStreamWrapper](./)\&&) | 移动赋值运算符。 |
| void [swap](./swap/)([BasicSystemIStreamWrapper](./)\&) | 如果它们不相等，则调用 swap *this 和 **right**。 |
## 类型别名

| 类型别名 | 描述 |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |
## 另请参阅

* 命名空间 [System::IO](../)
* 库 [Aspose.Slides](../../)