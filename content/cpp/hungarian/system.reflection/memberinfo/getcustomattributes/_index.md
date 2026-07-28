---
title: GetCustomAttributes()
second_title: Aspose.Slides C++ API Referencia
description: Visszaad egy tömböt, amely objektumokat tartalmaz, amelyek a jelenlegi objektum által képviselt típusra alkalmazott összes egyéni attribútumot képviselik.
type: docs
weight: 66
url: /hu/system.reflection/memberinfo/getcustomattributes/
---
## MemberInfo::GetCustomAttributes(const TypeInfo\&, bool) const metódus

Visszaad egy tömböt, amely objektumokat tartalmaz, amelyek a jelenlegi objektum által képviselt típusra alkalmazott összes egyéni attribútumot képviselik.

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit=false) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| attributeType | const [TypeInfo](../../../system/typeinfo/)\& | A keresett attribútum típusa. |
| inherit | **bool** | Azt is jelzi, hogy ellenőrizni kell-e az örökölt attribútumokat. |

## MemberInfo::GetCustomAttributes(bool) const metódus

Visszaad egy tömböt, amely objektumokat tartalmaz, amelyek a jelenlegi objektum által képviselt típusra alkalmazott összes egyéni attribútumot képviselik.

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(bool inherit=false) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| inherit | **bool** | Azt is jelzi, hogy ellenőrizni kell-e az örökölt attribútumokat. |

## Lásd még

* Típusdefiníció [ArrayPtr](../../../system/arrayptr/)
* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [Object](../../../system/object/)
* Osztály [TypeInfo](../../../system/typeinfo/)
* Osztály [MemberInfo](../)
* Névtér [System::Reflection](../../)
* Könyvtár [Aspose.Slides](../../../)