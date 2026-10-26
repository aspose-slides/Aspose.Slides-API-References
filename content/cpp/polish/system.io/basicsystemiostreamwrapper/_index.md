---
title: BasicSystemIOStreamWrapper
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Reprezentuje opakowanie podobne do std::iostream, które używa BasicSystemIOStreamBuf jako wewnętrznego bufora."
type: docs
weight: 53
url: /pl/system.io/basicsystemiostreamwrapper/
---
## BasicSystemIOStreamWrapper klasa

Reprezentuje opakowanie podobne do std::iostream, które używa [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) jako wewnętrznego bufora.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamWrapper : public std::basic_iostream<Elem, std::char_traits<Elem>>
```

## Metody

| Metoda | Opis |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamWrapper](./)\&&) | Używany w konstruktorze przenoszącym i operatorze przypisania przenoszącego do resetowania wskaźników i wywołania [swap()](./swap/). |
|  [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | Tworzy nową instancję [BasicSystemIOStreamWrapper](./). |
|  [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)(const [BasicSystemIOStreamWrapper](./)\&) | Konstruktor kopiujący. Usunięty. |
|  [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([BasicSystemIOStreamWrapper](./)\&&) | Konstruktor przenoszący. |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamWrapper](./)\&) | Operator przypisania kopiującego. Usunięty. |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamWrapper](./)\&&) | Operator przypisania przenoszącego. |
| void [swap](./swap/)([BasicSystemIOStreamWrapper](./)\&) | Wywołanie swap *this i **right**, jeśli nie są równe. |

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