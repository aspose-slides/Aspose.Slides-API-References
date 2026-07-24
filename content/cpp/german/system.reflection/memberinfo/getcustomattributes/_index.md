---
title: GetCustomAttributes()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt ein Array zurück, das Objekte enthält, die alle benutzerdefinierten Attribute repräsentieren, die auf den von dem aktuellen Objekt dargestellten Typ angewendet wurden.
type: docs
weight: 66
url: /de/system.reflection/memberinfo/getcustomattributes/
---
## MemberInfo::GetCustomAttributes(const TypeInfo\&, bool) const Methode

Gibt ein Array zurück, das Objekte enthält, die alle benutzerdefinierten Attribute repräsentieren, die auf den von dem aktuellen Objekt dargestellten Typ angewendet wurden.

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit=false) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| attributeType | const [TypeInfo](../../../system/typeinfo/)\& | Typ des Attributs, nach dem gesucht wird. |
| inherit | **bool** | Ob auch geerbte Attribute geprüft werden sollen. |

## MemberInfo::GetCustomAttributes(bool) const Methode

Gibt ein Array zurück, das Objekte enthält, die alle benutzerdefinierten Attribute repräsentieren, die auf den von dem aktuellen Objekt dargestellten Typ angewendet wurden.

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(bool inherit=false) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inherit | **bool** | Ob auch geerbte Attribute geprüft werden sollen. |

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [TypeInfo](../../../system/typeinfo/)
* Klasse [MemberInfo](../)
* Namensraum [System::Reflection](../../)
* Library [Aspose.Slides](../../../)