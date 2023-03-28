---
title: BasicSystemIOStreamWrapper
second_title: Aspose.Slides for C++ API Reference
description: "Represents a std::iostream-like wrapper that used BasicSystemIOStreamBuf as internal buffer."
type: docs
weight: 53
url: /cpp/system.io/basicsystemiostreamwrapper/
---
## BasicSystemIOStreamWrapper class


Represents a std::iostream-like wrapper that used [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) as internal buffer.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamWrapper : public std::basic_iostream<Elem, std::char_traits<Elem>>
```

## Methods

| Method | Description |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamWrapper](./)\&&) | Used in move constructor and move assignment operator to reset pointers and call [swap()](./swap/). |
|  [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | Constructs a new instance of the [BasicSystemIOStreamWrapper](./). |
|  [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)(const [BasicSystemIOStreamWrapper](./)\&) | Copy constructor. Deleted. |
|  [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([BasicSystemIOStreamWrapper](./)\&&) | Move constructor. |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamWrapper](./)\&) | Copy assignment operator. Deleted. |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamWrapper](./)\&&) | Move assignment operator. |
| void [swap](./swap/)([BasicSystemIOStreamWrapper](./)\&) | Call to swap *this and **right**, if they are not equal. |
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
