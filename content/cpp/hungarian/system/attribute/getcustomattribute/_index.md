---
title: GetCustomAttribute()
second_title: Aspose.Slides for C++ API-referencia
description: Visszaad egy egyedi attribútumot a megadott típusra alkalmazva a megadott típusra.
type: docs
weight: 1
url: /hu/system/attribute/getcustomattribute/
---
## Attribute::GetCustomAttribute(const TypeInfo\&, const TypeInfo\&) method

Visszaad egy egyedi attribútumot a megadott típusra alkalmazva a megadott típusra.

```cpp
static Object::ptr System::Attribute::GetCustomAttribute(const TypeInfo &type, const TypeInfo &attributeType)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Az attribútum típusa, amelyet lekérdeznek |
| attributeType | const [TypeInfo](../../typeinfo/)\& | Az attribútum lekérdezéséhez szükséges típus |

### Visszatérési érték

A lekérdezett attribútum vagy null, ha a megadott típus nem rendelkezik a megadott típusú attribútummal.

## Lásd még

* Typedef [ptr](../../object/ptr/)
* Osztály [TypeInfo](../../typeinfo/)
* Osztály [Attribute](../)
* Névtér [System](../../)
* Library [Aspose.Slides](../../../)