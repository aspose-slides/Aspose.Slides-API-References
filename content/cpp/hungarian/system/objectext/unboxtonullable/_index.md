---
title: UnboxToNullable()
second_title: Aspose.Slides C++ API referencia
description: Kibontja az objektumot nullable típusra.
type: docs
weight: 79
url: /hu/system/objectext/unboxtonullable/
---
## ObjectExt::UnboxToNullable(const SmartPtr\<Object\>\&, bool) metódus


Kibontja az objektumot nullable típusra.

```cpp
template<class T> static Nullable<T> System::ObjectExt::UnboxToNullable(const SmartPtr<Object> &obj, bool safe=1)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Cél típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) a kibontáshoz. |
| safe | **bool** | Ha true, hibakor esetén nullptr-et ad vissza, egyébként InvalidCastException-t dob. |

### Visszatérési érték

Kibontott nullable érték (lehet null).

## Lásd még

* Osztály [Nullable](../../nullable/)
* Osztály [SmartPtr](../../smartptr/)
* Osztály [Object](../../object/)
* Osztály [ObjectExt](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)