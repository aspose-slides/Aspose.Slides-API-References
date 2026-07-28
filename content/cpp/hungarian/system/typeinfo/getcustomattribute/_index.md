---
title: GetCustomAttribute()
second_title: Aspose.Slides C++ API referencia
description: Kikeresi a megadott típusú egyéni attribútumot, amely a jelenlegi objektum által képviselt típusra van alkalmazva.
type: docs
weight: 573
url: /hu/system/typeinfo/getcustomattribute/
---
## TypeInfo::GetCustomAttribute(const TypeInfo\&) const method


Kikeresi a megadott típusú egyéni attribútumot, amelyet a jelenlegi objektum által képviselt típusra alkalmaztak.

```cpp
ObjectPtr System::TypeInfo::GetCustomAttribute(const TypeInfo &attributeType) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | Az állandó referencia a(z) [TypeInfo](../) objektumra, amely a keresendő attribútum típusát képviseli |

### Visszatérési érték

Egy mutató egy olyan objektumra, amely a megtalált attribútumot képviseli, vagy null mutató, ha nem található a keresési feltételeknek megfelelő attribútum

## Lásd még

* Osztály [SmartPtr](../../smartptr/)
* Osztály [TypeInfo](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)