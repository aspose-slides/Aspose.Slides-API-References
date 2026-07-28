---
title: BasicSystemOStreamWrapper
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: "Reprezentuje opakowanie podobne do std::ostream, które używa BasicSystemIOStreamBuf jako wewnętrznego bufora."
type: docs
weight: 79
url: /pl/system.io/basicsystemostreamwrapper/
---
## BasicSystemOStreamWrapper klasa

Reprezentuje opakowanie podobne do std::ostream, które używa [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) jako wewnętrznego bufora.

```cpp
template<typename Elem,typename Traits>class BasicSystemOStreamWrapper : public std::basic_ostream<Elem, std::char_traits<Elem>>
```

## Metody

| Metoda | Opis |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemOStreamWrapper](./)\&&) | Używany w konstruktorze przenoszącym i operatorze przypisania przenoszącego do zresetowania wskaźników i wywołania [swap()](./swap/). |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | Tworzy nową instancję [BasicSystemOStreamWrapper](./). |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)(const [BasicSystemOStreamWrapper](./)\&) | Konstruktor kopiujący. Usunięty. |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([BasicSystemOStreamWrapper](./)\&&) | Konstruktor przenoszący. |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemOStreamWrapper](./)\&) | Operator przypisania kopiującego. Usunięty. |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemOStreamWrapper](./)\&&) | Operator przypisania przenoszącego. |
| void [swap](./swap/)([BasicSystemOStreamWrapper](./)\&) | Wywołanie swap *this i **right**, jeśli nie są równe. |

## Typedefy

| Typedef | Opis |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |

## Zobacz także

* Przestrzeń nazw [System::IO](../)
* Biblioteka [Aspose.Slides](../../)