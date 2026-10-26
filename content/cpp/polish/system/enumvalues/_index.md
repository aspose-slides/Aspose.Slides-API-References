---
title: EnumValues
second_title: Referencja API Aspose.Slides dla C++
description: Zapewnia informacje meta o stałych wyliczenia typu E.
type: docs
weight: 794
url: /pl/system/enumvalues/
---
## EnumValues klasa

Zapewnia informacje meta o stałych wyliczenia typu **E**.

```cpp
template<typename E,class Guard>class EnumValues : public System::EnumValuesBase
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| E | Typ wyliczenia |

## Metody

| Metoda | Opis |
| --- | --- |
|  [EnumValues](./enumvalues/)() | Tworzy instancję. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() const override | Zwraca tablicę zawierającą wszystkie nazwy wyliczenia **E**. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](../enumvaluesbase/getnames/)(const [TypeInfo](../typeinfo/)\&) | Pobiera tablicę nazw stałych w określonym wyliczeniu. |
| const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() const override | Zwraca podstawowy typ określonego wyliczenia. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](../enumvaluesbase/getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | Zwraca podstawowy typ określonego wyliczenia. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(const [String](../string/)\&, **bool**) const override | Zwraca zapakowaną wartość stałej wyliczenia o podanej nazwie. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(long) const override | Zwraca zapakowaną wartość stałej wyliczenia o podanej wartości. |
| [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)() const override | Zwraca tablicę zawierającą wszystkie wartości wyliczenia **E**. |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](../enumvaluesbase/getvalues/)(const [TypeInfo](../typeinfo/)\&) | Zwraca tablicę zawierającą wszystkie wartości określonego typu wyliczenia. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../enumvaluesbase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Zwraca obiekt reprezentujący wartość stałej wyliczenia określonego typu wyliczenia o podanej nazwie. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | Konwertuje podaną 64-bitową wartość całkowitą bez znaku na członka wyliczenia. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Konwertuje podany obiekt o wartości całkowitej na członka wyliczenia. |
| virtual  [~EnumValues](./~enumvalues/)() | Destruktor. |

## Zobacz także

* Klasa [EnumValuesBase](../enumvaluesbase/)
* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)