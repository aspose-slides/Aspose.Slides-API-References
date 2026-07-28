---
title: BasicSystemIStreamWrapper
second_title: Aspose.Slides dla C++ API Reference
description: "Reprezentuje opakowanie podobne do std::istream, które używa BasicSystemIOStreamBuf jako bufora wewnętrznego."
type: docs
weight: 66
url: /pl/system.io/basicsystemistreamwrapper/
---
## BasicSystemIStreamWrapper klasa

Reprezentuje opakowanie podobne do std::istream, które używa [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) jako bufora wewnętrznego.

```cpp
template<typename Elem,typename Traits>class BasicSystemIStreamWrapper : public std::basic_istream<Elem, std::char_traits<Elem>>
```

## Metody

| Metoda | Opis |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIStreamWrapper](./)\&&) | Używane w konstruktorze przenoszącym i operatorze przypisania przenoszącego do resetowania wskaźników i wywołania [swap()](./swap/). |
| [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | Tworzy nową instancję [BasicSystemIStreamWrapper](./). |
| [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)(const [BasicSystemIStreamWrapper](./)\&) | Konstruktor kopiujący. Usunięty. |
| [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([BasicSystemIStreamWrapper](./)\&&) | Konstruktor przenoszący. |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIStreamWrapper](./)\&) | Operator przypisania kopiującego. Usunięty. |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIStreamWrapper](./)\&&) | Operator przypisania przenoszącego. |
| void [swap](./swap/)([BasicSystemIStreamWrapper](./)\&) | Wywołuje zamianę *this i **right**, jeśli nie są równe. |

## Definicje typów

| Definicja typu | Opis |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |

## Zobacz także

* Przestrzeń nazw [System::IO](../)
* Biblioteka [Aspose.Slides](../../)