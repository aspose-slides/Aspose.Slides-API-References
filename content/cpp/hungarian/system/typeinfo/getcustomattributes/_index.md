---
title: GetCustomAttributes()
second_title: Aspose.Slides for C++ API hivatkozás
description: Visszaad egy tömböt, amely objektumokat tartalmaz, amelyek a típusra alkalmazott összes egyéni attribútumot képviselik.
type: docs
weight: 586
url: /hu/system/typeinfo/getcustomattributes/
---
## TypeInfo::GetCustomAttributes() const metódus

Visszaad egy tömböt, amely objektumokat tartalmaz, amelyek a típusra alkalmazott összes egyéni attribútumot képviselik.

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes() const
```

## TypeInfo::GetCustomAttributes(const TypeInfo\&, bool) const metódus

Visszaad egy tömböt, amely objektumokat tartalmaz, amelyek a típusra alkalmazott konkrét attribútumokat képviselik.

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | A keresett attribútum típusa. |
| inherit | **bool** | Megvizsgálja-e az örökölt attribútumokat is. |

## Lásd még

* Typedef [ArrayPtr](../../arrayptr/)
* Osztály [SmartPtr](../../smartptr/)
* Osztály [TypeInfo](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)