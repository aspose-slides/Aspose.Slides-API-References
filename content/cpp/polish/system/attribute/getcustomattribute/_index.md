---
title: GetCustomAttribute()
second_title: Aspose.Slides dla C++ – Referencja API
description: Zwraca niestandardowy atrybut określonego typu zastosowanego do określonego typu.
type: docs
weight: 1
url: /pl/system/attribute/getcustomattribute/
---
## Attribute::GetCustomAttribute(const TypeInfo\&, const TypeInfo\&) metoda


Zwraca niestandardowy atrybut określonego typu zastosowanego do określonego typu.

```cpp
static Object::ptr System::Attribute::GetCustomAttribute(const TypeInfo &type, const TypeInfo &attributeType)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Atrybut typu, który jest pobierany |
| attributeType | const [TypeInfo](../../typeinfo/)\& | Typ atrybutu do pobrania |

### Wartość zwracana

Pobrany atrybut lub null, jeśli określony typ nie posiada atrybutu podanego typu.

## Zobacz także

* Definicja typu [ptr](../../object/ptr/)
* Klasa [TypeInfo](../../typeinfo/)
* Klasa [Attribute](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)