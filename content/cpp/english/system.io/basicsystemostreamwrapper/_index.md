---
title: BasicSystemOStreamWrapper
second_title: Aspose.Slides for C++ API Reference
description: "Represents a std::ostream-like wrapper that used BasicSystemIOStreamBuf as internal buffer."
type: docs
weight: 79
url: /system.io/basicsystemostreamwrapper/
---
## BasicSystemOStreamWrapper class


Represents a std::ostream-like wrapper that used [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) as internal buffer.

```cpp
template<typename Elem,typename Traits>class BasicSystemOStreamWrapper : public std::basic_ostream<Elem, std::char_traits<Elem>>
```

## Methods

| Method | Description |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemOStreamWrapper](./)\&&) | Used in move constructor and move assignment operator to reset pointers and call [swap()](./swap/). |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | Constructs a new instance of the [BasicSystemOStreamWrapper](./). |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)(const [BasicSystemOStreamWrapper](./)\&) | Copy constructor. Deleted. |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([BasicSystemOStreamWrapper](./)\&&) | Move constructor. |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemOStreamWrapper](./)\&) | Copy assignment operator. Deleted. |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemOStreamWrapper](./)\&&) | Move assignment operator. |
| void [swap](./swap/)([BasicSystemOStreamWrapper](./)\&) | Call to swap *this and **right**, if they are not equal. |
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