---
title: BasicSystemIOStreamWrapper
second_title: Aspose.Slides för C++ API-referens
description: "Representerar en std::iostream-liknande wrapper som använder BasicSystemIOStreamBuf som intern buffert."
type: docs
weight: 53
url: /sv/system.io/basicsystemiostreamwrapper/
---
## BasicSystemIOStreamWrapper klass

Representerar en std::iostream-liknande wrapper som använder [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) som intern buffert.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamWrapper : public std::basic_iostream<Elem, std::char_traits<Elem>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamWrapper](./)\&&) | Används i flyttkonstruktor och flytttilldelningsoperator för att återställa pekare och anropa [swap()](./swap/). |
|  [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | Skapar en ny instans av [BasicSystemIOStreamWrapper](./). |
|  [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)(const [BasicSystemIOStreamWrapper](./)\&) | Kopieringskonstruktor. Borttagen. |
|  [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([BasicSystemIOStreamWrapper](./)\&&) | Flyttkonstruktor. |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamWrapper](./)\&) | Kopieringstilldelningsoperator. Borttagen. |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamWrapper](./)\&&) | Flytttilldelningsoperator. |
| void [swap](./swap/)([BasicSystemIOStreamWrapper](./)\&) | Anrop för att byta *this och **right**, om de inte är lika. |

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