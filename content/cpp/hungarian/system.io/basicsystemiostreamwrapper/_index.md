---
title: BasicSystemIOStreamWrapper
second_title: Aspose.Slides a C++ API referencia
description: "Egy std::iostream-szerű csomagolót reprezentál, amely a BasicSystemIOStreamBuf-ot használja belső pufferként."
type: docs
weight: 53
url: /hu/system.io/basicsystemiostreamwrapper/
---
## BasicSystemIOStreamWrapper osztály

Egy std::iostream-szerű csomagoló, amely [BasicSystemIOStreamBuf](../basicsystemiostreambuf/)-t használ belső pufferként.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamWrapper : public std::basic_iostream<Elem, std::char_traits<Elem>>
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamWrapper](./)\&&) | Used in move constructor and move assignment operator to reset pointers and call [swap()](./swap/). |
|  [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | Constructs a new instance of the [BasicSystemIOStreamWrapper](./). |
|  [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)(const [BasicSystemIOStreamWrapper](./)\&) | Copy constructor. Deleted. |
|  [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([BasicSystemIOStreamWrapper](./)\&&) | Move constructor. |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamWrapper](./)\&) | Copy assignment operator. Deleted. |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamWrapper](./)\&&) | Move assignment operator. |
| void [swap](./swap/)([BasicSystemIOStreamWrapper](./)\&) | Call to swap *this and **right**, if they are not equal. |

## Typedef-ek

| Typedef | Leírás |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |

## Lásd még

* Névtér [System::IO](../)
* Könyvtár [Aspose.Slides](../../)