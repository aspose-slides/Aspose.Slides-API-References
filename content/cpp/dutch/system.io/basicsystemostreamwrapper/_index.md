---
title: BasicSystemOStreamWrapper
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt een std::ostream-achtige wrapper voor die BasicSystemIOStreamBuf als interne buffer gebruikte."
type: docs
weight: 79
url: /nl/system.io/basicsystemostreamwrapper/
---
## BasicSystemOStreamWrapper klasse

Stelt een std::ostream-achtige wrapper voor die [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) als interne buffer gebruikte.

```cpp
template<typename Elem,typename Traits>class BasicSystemOStreamWrapper : public std::basic_ostream<Elem, std::char_traits<Elem>>
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemOStreamWrapper](./)\&&) | Used in move constructor and move assignment operator to reset pointers and call [swap()](./swap/). |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | Constructs a new instance of the [BasicSystemOStreamWrapper](./). |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)(const [BasicSystemOStreamWrapper](./)\&) | Copy constructor. Deleted. |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([BasicSystemOStreamWrapper](./)\&&) | Move constructor. |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemOStreamWrapper](./)\&) | Copy assignment operator. Deleted. |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemOStreamWrapper](./)\&&) | Move assignment operator. |
| void [swap](./swap/)([BasicSystemOStreamWrapper](./)\&) | Call to swap *this and **right**, if they are not equal. |

## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |

## Zie ook

* Namespace [System::IO](../)
* Bibliotheek [Aspose.Slides](../../)