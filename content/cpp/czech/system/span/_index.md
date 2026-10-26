---
title: Span
second_title: Aspose.Slides pro C++ - reference API
description: "Představuje souvislý úsek libovolné paměti podobný std::span z C++20."
type: docs
weight: 1262
url: /cs/system/span/
---
## Span třída


Představuje souvislý úsek libovolné paměti podobný std::span z C++20.

```cpp
template<typename T>class Span : public System::Details::SpanCore<T, Span<T>, Span<T>>
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve span. Tato třída poskytuje typově bezpečný způsob práce s souvislými sekvencemi objektů. Lze ji použít k zabalení polí, zásobníkových polí nebo surových ukazatelů při zachování kontroly mezí. [Span](./) nevlastní paměť, na kterou ukazuje – je to jen pohled na existující paměť. |
## Metody

| Metoda | Popis |
| --- | --- |
| void [Clear](./clear/)() const | Vyčistí obsah span nastavením všech prvků na výchozí hodnotu. |
| void [Fill](./fill/)(const T\&) const | Naplní span zadanou hodnotou. |
| static [ThisType](./) [to_Span](./to_span/)(const typename BaseType::ArrayPtrT\&) | Převede pole na [Span](./). |

## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)