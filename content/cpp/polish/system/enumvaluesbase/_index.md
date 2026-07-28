---
title: EnumValuesBase
second_title: Referencja API Aspose.Slides dla C++
description: Klasa bazowa dla klasy, która reprezentuje informacje meta typu wyliczeniowego.
type: docs
weight: 807
url: /pl/system/enumvaluesbase/
---
## EnumValuesBase klasa

Klasa bazowa dla klasy, która reprezentuje informacje meta typu wyliczeniowego.

```cpp
class EnumValuesBase
```

## Metody

| Metoda | Opis |
| --- | --- |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)(const [TypeInfo](../typeinfo/)\&) | Zwraca tablicę nazw stałych w określonym typie wyliczeniowym. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | Zwraca podstawowy typ określonego typu wyliczeniowego. |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)(const [TypeInfo](../typeinfo/)\&) | Zwraca tablicę zawierającą wszystkie wartości określonego typu wyliczeniowego. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](./parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Zwraca obiekt, który reprezentuje wartość stałej wyliczeniowej określonego typu wyliczeniowego o podanej nazwie. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | Konwertuje podaną 64-bitową liczbę całkowitą bez znaku na element wyliczenia. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Konwertuje podany obiekt z wartością całkowitą na element wyliczenia. |

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)