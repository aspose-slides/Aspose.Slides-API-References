---
title: BasicSystemOStreamWrapper
second_title: Aspose.Slides för C++ API-referens
description: "Representerar en std::ostream-like wrapper som använde BasicSystemIOStreamBuf som intern buffert."
type: docs
weight: 79
url: /sv/system.io/basicsystemostreamwrapper/
---
## BasicSystemOStreamWrapper klass

Representerar en std::ostream-liknande wrapper som använde [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) som intern buffert.

```cpp
template<typename Elem,typename Traits>class BasicSystemOStreamWrapper : public std::basic_ostream<Elem, std::char_traits<Elem>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemOStreamWrapper](./)\&&) | Används i flyttkonstruktorn och flytttilldelningsoperatorn för att återställa pekare och anropa [swap()](./swap/). |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | Skapar en ny instans av [BasicSystemOStreamWrapper](./). |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)(const [BasicSystemOStreamWrapper](./)\&) | Kopieringskonstruktor. Borttagen. |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([BasicSystemOStreamWrapper](./)\&&) | Flyttkonstruktor. |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemOStreamWrapper](./)\&) | Kopieringstilldelningsoperator. Borttagen. |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemOStreamWrapper](./)\&&) | Flytttilldelningsoperator. |
| void [swap](./swap/)([BasicSystemOStreamWrapper](./)\&) | Anrop för att byta *this och **right**, om de inte är lika. |

## Typdef

| Typdef | Beskrivning |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |

## Se också

* Namnrymd [System::IO](../)
* Bibliotek [Aspose.Slides](../../)