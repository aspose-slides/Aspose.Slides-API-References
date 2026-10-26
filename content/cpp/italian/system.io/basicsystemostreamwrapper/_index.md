---
title: BasicSystemOStreamWrapper
second_title: Riferimento API di Aspose.Slides per C++
description: "Rappresenta un wrapper simile a std::ostream che utilizza BasicSystemIOStreamBuf come buffer interno."
type: docs
weight: 79
url: /it/system.io/basicsystemostreamwrapper/
---
## BasicSystemOStreamWrapper classe

Rappresenta un wrapper simile a std::ostream che utilizza [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) come buffer interno.

```cpp
template<typename Elem,typename Traits>class BasicSystemOStreamWrapper : public std::basic_ostream<Elem, std::char_traits<Elem>>
```

## Metodi

| Method | Descrizione |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemOStreamWrapper](./)\&&) | Used in move constructor and move assignment operator to reset pointers and call [swap()](./swap/). |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | Constructs a new instance of the [BasicSystemOStreamWrapper](./). |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)(const [BasicSystemOStreamWrapper](./)\&) | Copy constructor. Deleted. |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([BasicSystemOStreamWrapper](./)\&&) | Move constructor. |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemOStreamWrapper](./)\&) | Copy assignment operator. Deleted. |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemOStreamWrapper](./)\&&) | Move assignment operator. |
| void [swap](./swap/)([BasicSystemOStreamWrapper](./)\&) | Call to swap *this and **right**, if they are not equal. |

## Typedefs

| Typedef | Descrizione |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |

## Vedi anche

* Spazio dei nomi [System::IO](../)
* Libreria [Aspose.Slides](../../)