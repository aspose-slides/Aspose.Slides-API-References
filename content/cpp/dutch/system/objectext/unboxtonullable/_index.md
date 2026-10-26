---
title: UnboxToNullable()
second_title: Aspose.Slides voor C++ API Referentie
description: Deboxeert object naar een nullable type.
type: docs
weight: 79
url: /nl/system/objectext/unboxtonullable/
---
## ObjectExt::UnboxToNullable(const SmartPtr\<Object\>\&, bool) methode

Deboxeert object naar een nullable type.

```cpp
template<class T> static Nullable<T> System::ObjectExt::UnboxToNullable(const SmartPtr<Object> &obj, bool safe=1)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Doeltype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) om te deboxen. |
| safe | **bool** | Als true, return nullptr bij falen, anders throw InvalidCastException. |

### Retourwaarde

Gedeboxeerde nullable waarde (kan null zijn).

## Zie ook

* Klasse [Nullable](../../nullable/)
* Klasse [SmartPtr](../../smartptr/)
* Klasse [Object](../../object/)
* Klasse [ObjectExt](../)
* Namespace [System](../../)
* Bibliotheek [Aspose.Slides](../../../)