---
title: BasicSystemIOStreamBuf
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt een buffer voor die System::IO::Stream-achtige streams omsluit en het mogelijk maakt ze te gebruiken als een interne buffer voor std::iostream-achtige streams."
type: docs
weight: 40
url: /nl/system.io/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf klasse

Stelt een buffer voor die [System::IO::Stream](../stream/)-achtige streams omsluit en het mogelijk maakt ze te gebruiken als een interne buffer voor std::iostream-achtige streams.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamBuf : public std::basic_streambuf<Elem, std::char_traits<Elem>>
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamBuf](./)\&&) | Gebruikt in de move-constructor en move-toewijzingsoperator om pointers te resetten en [swap()](./swap/) aan te roepen. |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)() | Construeert een nieuw exemplaar van de [BasicSystemIOStreamBuf](./). |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/), const std::locale\&) | Construeert een nieuw exemplaar van de [BasicSystemIOStreamBuf](./). |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [BasicSystemIOStreamBuf](./)\&) | Copy-constructor. Verwijderd. |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)([BasicSystemIOStreamBuf](./)\&&) | Move-constructor. |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamBuf](./)\&) | Copy-toewijzingsoperator. Verwijderd. |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamBuf](./)\&&) | Move-toewijzingsoperator. |
| void [swap](./swap/)([BasicSystemIOStreamBuf](./)\&) | Aanroep om *this en right te wisselen, indien ze niet gelijk zijn. |
|  [~BasicSystemIOStreamBuf](./~basicsystemiostreambuf/)() override | Destructor. |

## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mysb](./mysb/) |  |
| [int_type](./int_type/) |  |
| [pos_type](./pos_type/) |  |
| [off_type](./off_type/) |  |

## Zie ook

* Namespace [System::IO](../)
* Bibliotheek [Aspose.Slides](../../)