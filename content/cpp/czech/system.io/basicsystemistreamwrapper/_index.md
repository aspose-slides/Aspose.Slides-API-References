---
title: BasicSystemIStreamWrapper
second_title: Aspose.Slides pro C++ API Reference
description: "Representuje obal podobný std::istream, který používá BasicSystemIOStreamBuf jako interní buffer."
type: docs
weight: 66
url: /cs/system.io/basicsystemistreamwrapper/
---
## BasicSystemIStreamWrapper třída

Represents a std::istream-like wrapper that used [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) as internal buffer.

```cpp
template<typename Elem,typename Traits>class BasicSystemIStreamWrapper : public std::basic_istream<Elem, std::char_traits<Elem>>
```

## Metody

| Metoda | Popis |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIStreamWrapper](./)\&&) | Used in move constructor and move assignment operator to reset pointers and call [swap()](./swap/). |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | Constructs a new instance of the [BasicSystemIStreamWrapper](./). |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)(const [BasicSystemIStreamWrapper](./)\&) | Copy constructor. Deleted. |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([BasicSystemIStreamWrapper](./)\&&) | Move constructor. |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIStreamWrapper](./)\&) | Copy assignment operator. Deleted. |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIStreamWrapper](./)\&&) | Move assignment operator. |
| void [swap](./swap/)([BasicSystemIStreamWrapper](./)\&) | Call to swap *this and **right**, if they are not equal. |

## Typedefy

| Typedef | Popis |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |

## Viz také

* Obor názvů [System::IO](../)
* Knihovna [Aspose.Slides](../../)