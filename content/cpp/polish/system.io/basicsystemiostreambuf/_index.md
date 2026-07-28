---
title: BasicSystemIOStreamBuf
second_title: Aspose.Slides – dokumentacja API dla C++
description: "Reprezentuje bufor, który opakowuje strumienie podobne do System::IO::Stream i pozwala używać ich jako wewnętrzny bufor strumieni podobnych do std::iostream."
type: docs
weight: 40
url: /pl/system.io/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf klasa


Reprezentuje bufor, który opakowuje [System::IO::Stream](../stream/)-like streams i umożliwia ich użycie jako wewnętrzny bufor std::iostream-like streams.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamBuf : public std::basic_streambuf<Elem, std::char_traits<Elem>>
```

## Metody

| Metoda | Opis |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamBuf](./)\&&) | Używane w konstruktorze przenoszącym i operatorze przypisania przenoszącego do resetowania wskaźników i wywołania [swap()](./swap/). |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)() | Tworzy nową instancję [BasicSystemIOStreamBuf](./). |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/), const std::locale\&) | Tworzy nową instancję [BasicSystemIOStreamBuf](./). |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [BasicSystemIOStreamBuf](./)\&) | Konstruktor kopiujący. Usunięty. |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)([BasicSystemIOStreamBuf](./)\&&) | Konstruktor przenoszący. |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamBuf](./)\&) | Operator przypisania kopiującego. Usunięty. |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamBuf](./)\&&) | Operator przypisania przenoszącego. |
| void [swap](./swap/)([BasicSystemIOStreamBuf](./)\&) | Wywołanie zamiany *this i right, jeśli nie są równe. |
|  [~BasicSystemIOStreamBuf](./~basicsystemiostreambuf/)() override | Destruktor. |

## Typedefs

| Typedef | Opis |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mysb](./mysb/) |  |
| [int_type](./int_type/) |  |
| [pos_type](./pos_type/) |  |
| [off_type](./off_type/) |  |

## Zobacz także

* Przestrzeń nazw [System::IO](../)
* Biblioteka [Aspose.Slides](../../)