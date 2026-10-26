---
title: operator!=()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Určuje, zda aktuální a specifikované objekty TypeInfo nejsou rovny.
type: docs
weight: 456
url: /cs/system/typeinfo/operator_not_equal/
---
## TypeInfo::operator!=(const TypeInfo\&) const metoda


Určuje, zda aktuální a specifikované objekty [TypeInfo](../) nejsou rovny.

```cpp
bool System::TypeInfo::operator!=(const TypeInfo &info) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| info | const [TypeInfo](../)\& | Objekt [TypeInfo](../), s nímž se porovnává |

### Návratová hodnota

True pokud jsou haše objektů různé, jinak - false

## TypeInfo::operator!=(std::nullptr_t) const metoda


Určuje, zda aktuální objekt [TypeInfo](../) není null-objekt, tj. představuje nějaký typ.

```cpp
bool System::TypeInfo::operator!=(std::nullptr_t) const
```


### Návratová hodnota

True pokud aktuální objekt [TypeInfo](../) není null-objekt, jinak - false

## Viz také

* Třída [TypeInfo](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)