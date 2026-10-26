---
title: BasicSystemIOStreamBuf
second_title: Aspose.Slides för C++ API-referens
description: "Representerar en buffert som omsluter System::IO::Stream-liknande strömmar och gör att de kan användas som en intern buffert för std::iostream-liknande strömmar."
type: docs
weight: 40
url: /sv/system.io/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf klass

Representerar en buffert som omsluter [System::IO::Stream](../stream/)-liknande strömmar och gör att de kan användas som en intern buffert för std::iostream-like strömmar.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamBuf : public std::basic_streambuf<Elem, std::char_traits<Elem>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamBuf](./)\&&) | Används i flyttkonstruktorn och flytttilldelningsoperatorn för att återställa pekare och anropa [swap()](./swap/). |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)() | Skapar en ny instans av [BasicSystemIOStreamBuf](./). |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/), const std::locale\&) | Skapar en ny instans av [BasicSystemIOStreamBuf](./). |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [BasicSystemIOStreamBuf](./)\&) | Kopieringskonstruktor. Borttagen. |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)([BasicSystemIOStreamBuf](./)\&&) | Flyttkonstruktor. |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamBuf](./)\&) | Kopieringsoperator för tilldelning. Borttagen. |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamBuf](./)\&&) | Flyttoperator för tilldelning. |
| void [swap](./swap/)([BasicSystemIOStreamBuf](./)\&) | Anrop för att byta *this och right, om de inte är lika. |
|  [~BasicSystemIOStreamBuf](./~basicsystemiostreambuf/)() override | Destruktor. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mysb](./mysb/) |  |
| [int_type](./int_type/) |  |
| [pos_type](./pos_type/) |  |
| [off_type](./off_type/) |  |
## Se även

* Namnrymd [System::IO](../)
* Bibliotek [Aspose.Slides](../../)