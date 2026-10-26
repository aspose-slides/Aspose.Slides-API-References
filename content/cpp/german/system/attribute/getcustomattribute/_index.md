---
title: GetCustomAttribute()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt ein benutzerdefiniertes Attribut eines angegebenen Typs zurück, das auf den angegebenen Typ angewendet wird.
type: docs
weight: 1
url: /de/system/attribute/getcustomattribute/
---
## Attribute::GetCustomAttribute(const TypeInfo\&, const TypeInfo\&) Methode

Gibt ein benutzerdefiniertes Attribut eines angegebenen Typs zurück, das auf den angegebenen Typ angewendet wird.

```cpp
static Object::ptr System::Attribute::GetCustomAttribute(const TypeInfo &type, const TypeInfo &attributeType)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Typ, dessen Attribut abgerufen wird |
| attributeType | const [TypeInfo](../../typeinfo/)\& | Typ des abzurufenden Attributs |

### Rückgabewert

Ein abgerufenes Attribut oder null, wenn der angegebene Typ kein Attribut des angegebenen Typs besitzt.

## Siehe auch

* Typdefinition [ptr](../../object/ptr/)
* Klasse [TypeInfo](../../typeinfo/)
* Klasse [Attribute](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)