---
title: GetCustomAttribute()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací vlastní atribut daného typu aplikovaného na specifikovaný typ.
type: docs
weight: 1
url: /cs/system/attribute/getcustomattribute/
---
## Attribute::GetCustomAttribute(const TypeInfo\&, const TypeInfo\&) metoda

Vrací vlastní atribut daného typu aplikovaného na zadaný typ.

```cpp
static Object::ptr System::Attribute::GetCustomAttribute(const TypeInfo &type, const TypeInfo &attributeType)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Typ atributu, který je načten |
| attributeType | const [TypeInfo](../../typeinfo/)\& | Typ atributu k načtení |

### Návratová hodnota

Načtený atribut nebo null, pokud zadaný typ nemá atribut daného typu.

## Viz také

* Definice typu [ptr](../../object/ptr/)
* Třída [TypeInfo](../../typeinfo/)
* Třída [Attribute](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)