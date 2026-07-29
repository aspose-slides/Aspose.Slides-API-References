---
title: BasicSystemIStreamWrapper
second_title: Aspose.Slides för C++ API-referens
description: "Representerar ett std::istream-liknande omslag som använde BasicSystemIOStreamBuf som intern buffert."
type: docs
weight: 66
url: /sv/system.io/basicsystemistreamwrapper/
---
## BasicSystemIStreamWrapper klass

Representerar ett std::istream-liknande omslag som använde [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) som intern buffert.

```cpp
template<typename Elem,typename Traits>class BasicSystemIStreamWrapper : public std::basic_istream<Elem, std::char_traits<Elem>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIStreamWrapper](./)\&&) | Används i flyttkonstruktorn och flytttilldelningsoperatorn för att återställa pekare och anropa [swap()](./swap/). |
| [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | Skapar en ny instans av [BasicSystemIStreamWrapper](./). |
| [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)(const [BasicSystemIStreamWrapper](./)\&) | Kopieringskonstruktor. Borttagen. |
| [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([BasicSystemIStreamWrapper](./)\&&) | Flyttkonstruktor. |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIStreamWrapper](./)\&) | Kopieringstilldelningsoperator. Borttagen. |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIStreamWrapper](./)\&&) | Flytttilldelningsoperator. |
| void [swap](./swap/)([BasicSystemIStreamWrapper](./)\&) | Anrop för att byta *this och **right**, om de inte är lika. |

## Typdefinitioner

| Typdefinition | Beskrivning |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |

## Se även

* Namnrymd [System::IO](../)
* Bibliotek [Aspose.Slides](../../)