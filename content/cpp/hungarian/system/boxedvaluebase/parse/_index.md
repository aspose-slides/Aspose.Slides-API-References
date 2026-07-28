---
title: Parse()
second_title: Aspose.Slides for C++ API Referencia
description: Az adott felsorolásban a megadott névvel rendelkező felsorolásállandó értékét csomagolja be. Egy paraméter határozza meg, hogy a kis- és nagybetűk figyelmen kívül hagyása szükséges-e a felsorolásállandó nevét megadó karakterlánc értelmezésekor.
type: docs
weight: 53
url: /hu/system/boxedvaluebase/parse/
---
## BoxedValueBase::Parse(const TypeInfo\&, const String\&, bool) metódus


Az adott felsorolásban a megadott névvel rendelkező felsorolásállandó értékét csomagolja be. Egy paraméter határozza meg, hogy a kis- és nagybetűk figyelmen kívül hagyása szükséges-e a felsorolásállandó nevét megadó karakterlánc értelmezésekor.

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```


### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Specifies the type of the enumeration |
| str | const [String](../../string/)\& | The name of the enumeration constant, value of which is to be boxed |
| ignoreCase | **bool** | Specifies if case should be ignored when interpreting the string representing the name of the enumeration constant |

### Visszatérési érték

A shared pointer to the object representing boxed value of the specified enumeration constant

## BoxedValueBase::Parse(const TypeInfo\&, const String\&) metódus


A megadott névvel rendelkező felsorolásállandó értékét csomagolja be a megadott felsorolásban.

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str)
```


### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Specifies the type of the enumeration |
| str | const [String](../../string/)\& | The name of the enumeration constant, value of which is to be boxed |

### Visszatérési érték

A shared pointer to the object representing boxed value of the specified enumeration constant

## Lásd még

* Typedef [SharedPtr](../../sharedptr/)
* Osztály [Object](../../object/)
* Osztály [TypeInfo](../../typeinfo/)
* Osztály [String](../../string/)
* Osztály [BoxedValueBase](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)