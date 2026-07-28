---
title: operator!=()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Określa, czy bieżący i określony obiekty TypeInfo nie są równe.
type: docs
weight: 456
url: /pl/system/typeinfo/operator_not_equal/
---
## TypeInfo::operator!=(const TypeInfo\&) const metoda


Określa, czy bieżące i określone obiekty [TypeInfo](../) nie są równe.

```cpp
bool System::TypeInfo::operator!=(const TypeInfo &info) const
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| info | const [TypeInfo](../)\& | Obiekt [TypeInfo](../) do porównania |

### Wartość zwracana

True, jeśli skróty obiektów nie są równe, w przeciwnym razie - false

## TypeInfo::operator!=(std::nullptr_t) const metoda


Określa, czy bieżący obiekt [TypeInfo](../) nie jest obiektem null, tzn. reprezentuje jakiś typ.

```cpp
bool System::TypeInfo::operator!=(std::nullptr_t) const
```


### Wartość zwracana

True, jeśli bieżący obiekt [TypeInfo](../) nie jest obiektem null, w przeciwnym razie - false

## Zobacz także

* Klasa [TypeInfo](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)