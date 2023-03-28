---
title: BasicSystemIOStreamBuf
second_title: Aspose.Slides for C++ API Reference
description: "Represents a buffer that wraps System::IO::Stream-like streams and allows them to be used as an std::iostream-like streams internal buffer."
type: docs
weight: 40
url: /cpp/system.io/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf class


Represents a buffer that wraps [System::IO::Stream](../stream/)-like streams and allows them to be used as an std::iostream-like streams internal buffer.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamBuf : public std::basic_streambuf<Elem, std::char_traits<Elem>>
```

## Methods

| Method | Description |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamBuf](./)\&&) | Used in move constructor and move assignment operator to reset pointers and call [swap()](./swap/). |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)() | Constructs a new instance of the [BasicSystemIOStreamBuf](./). |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/), const std::locale\&) | Constructs a new instance of the [BasicSystemIOStreamBuf](./). |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [BasicSystemIOStreamBuf](./)\&) | Copy constructor. Deleted. |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)([BasicSystemIOStreamBuf](./)\&&) | Move constructor. |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamBuf](./)\&) | Copy assignment operator. Deleted. |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamBuf](./)\&&) | Move assignment operator. |
| void [swap](./swap/)([BasicSystemIOStreamBuf](./)\&) | Call to swap *this and right, if they are not equal. |
|  [~BasicSystemIOStreamBuf](./~basicsystemiostreambuf/)() override | Destructor. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mysb](./mysb/) |  |
| [int_type](./int_type/) |  |
| [pos_type](./pos_type/) |  |
| [off_type](./off_type/) |  |
## See Also

* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)
