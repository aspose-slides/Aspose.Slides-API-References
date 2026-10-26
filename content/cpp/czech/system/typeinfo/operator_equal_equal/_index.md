---
title: operator==()
second_title: Aspose.Slides pro C++ API Reference
description: Určuje, zda jsou aktuální a specifikované objekty TypeInfo rovny.
type: docs
weight: 443
url: /cs/system/typeinfo/operator_equal_equal/
---
## TypeInfo::operator==(const TypeInfo\&) const metoda


Určuje, zda jsou aktuální a specifikované [TypeInfo](../) objekty rovny.

```cpp
bool System::TypeInfo::operator==(const TypeInfo &info) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| info | const [TypeInfo](../)\& | [TypeInfo](../) objekt, se kterým se porovnává |

### Návratová hodnota

True pokud jsou haše objektů stejné, jinak - false

## TypeInfo::operator==(std::nullptr_t) const metoda


Určuje, zda je aktuální [TypeInfo](../) objekt null-objekt, tj. nepředstavuje žádný typ.

```cpp
bool System::TypeInfo::operator==(std::nullptr_t) const
```


### Návratová hodnota

True pokud je aktuální [TypeInfo](../) objekt null-objekt, jinak - false

## Viz také

* Třída [TypeInfo](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)