---
title: BasicSystemIStreamWrapper
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt een std::istream-achtige wrapper voor die BasicSystemIOStreamBuf gebruikt als interne buffer."
type: docs
weight: 66
url: /nl/system.io/basicsystemistreamwrapper/
---
## BasicSystemIStreamWrapper klasse

Stelt een std::istream-achtige wrapper voor die [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) gebruikt als interne buffer.

```cpp
template<typename Elem,typename Traits>class BasicSystemIStreamWrapper : public std::basic_istream<Elem, std::char_traits<Elem>>
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIStreamWrapper](./)\&&) | Gebruikt in de move-constructor en move-assignment-operator om pointers te resetten en [swap()](./swap/) aan te roepen. |
| [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | Construeert een nieuw exemplaar van de [BasicSystemIStreamWrapper](./). |
| [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)(const [BasicSystemIStreamWrapper](./)\&) | Copy-constructor. Verwijderd. |
| [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([BasicSystemIStreamWrapper](./)\&&) | Move-constructor. |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIStreamWrapper](./)\&) | Copy-assignment-operator. Verwijderd. |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIStreamWrapper](./)\&&) | Move-assignment-operator. |
| void [swap](./swap/)([BasicSystemIStreamWrapper](./)\&) | Aanroep om *this en **right** te verwisselen, indien ze niet gelijk zijn. |

## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |

## Zie ook

* Naamruimte [System::IO](../)
* Bibliotheek [Aspose.Slides](../../)