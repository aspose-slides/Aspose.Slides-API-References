---
title: GetCustomAttributes()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt ein Array zurück, das Objekte enthält, die alle auf den Typ angewendeten benutzerdefinierten Attribute darstellen.
type: docs
weight: 586
url: /de/system/typeinfo/getcustomattributes/
---
## TypeInfo::GetCustomAttributes() const Methode


Gibt ein Array zurück, das Objekte enthält, die alle auf den Typ angewendeten benutzerdefinierten Attribute darstellen.

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes() const
```

## TypeInfo::GetCustomAttributes(const TypeInfo\&, bool) const Methode


Gibt ein Array zurück, das Objekte enthält, die die auf den Typ angewendeten spezifischen Attribute darstellen.

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit) const
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | Typ des Attributs, nach dem gesucht wird. |
| inherit | **bool** | Ob auch nach geerbten Attributen gesucht werden soll. |

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [SmartPtr](../../smartptr/)
* Klasse [TypeInfo](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)