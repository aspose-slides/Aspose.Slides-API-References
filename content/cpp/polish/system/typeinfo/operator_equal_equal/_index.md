---
title: operator==()
second_title: Referencja API Aspose.Slides dla C++
description: Określa, czy bieżące i określone obiekty TypeInfo są równe.
type: docs
weight: 443
url: /pl/system/typeinfo/operator_equal_equal/
---
## TypeInfo::operator==(const TypeInfo\&) const metoda

Określa, czy bieżące i określone [TypeInfo](../) obiekty są równe.

```cpp
bool System::TypeInfo::operator==(const TypeInfo &info) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| info | const [TypeInfo](../)\& | Obiekt [TypeInfo](../) do porównania |

### Wartość zwracana

True jeśli hashe obiektów są równe, w przeciwnym razie - false

## TypeInfo::operator==(std::nullptr_t) const metoda

Określa, czy bieżący [TypeInfo](../) obiekt jest obiektem null, tzn. nie reprezentuje żadnego typu.

```cpp
bool System::TypeInfo::operator==(std::nullptr_t) const
```

### Wartość zwracana

True jeśli bieżący [TypeInfo](../) obiekt jest obiektem null, w przeciwnym razie - false

## Zobacz także

* Klasa [TypeInfo](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)