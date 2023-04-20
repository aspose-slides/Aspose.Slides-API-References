---
title: BasicSystemIStreamWrapper
second_title: Aspose.Slides for C++ API Reference
description: "Represents a std::istream-like wrapper that used BasicSystemIOStreamBuf as internal buffer."
type: docs
weight: 66
url: /cpp/system.io/basicsystemistreamwrapper/
---
## BasicSystemIStreamWrapper class


Represents a std::istream-like wrapper that used [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) as internal buffer.

```cpp
template<typename Elem,typename Traits>class BasicSystemIStreamWrapper : public std::basic_istream<Elem, std::char_traits<Elem>>
```

## Methods

| Method | Description |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIStreamWrapper](./)\&&) | Used in move constructor and move assignment operator to reset pointers and call [swap()](./swap/). |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | Constructs a new instance of the [BasicSystemIStreamWrapper](./). |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)(const [BasicSystemIStreamWrapper](./)\&) | Copy constructor. Deleted. |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([BasicSystemIStreamWrapper](./)\&&) | Move constructor. |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIStreamWrapper](./)\&) | Copy assignment operator. Deleted. |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIStreamWrapper](./)\&&) | Move assignment operator. |
| void [swap](./swap/)([BasicSystemIStreamWrapper](./)\&) | Call to swap *this and **right**, if they are not equal. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |
## See Also

* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)