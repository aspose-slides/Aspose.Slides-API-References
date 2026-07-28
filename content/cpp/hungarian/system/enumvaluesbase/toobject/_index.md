---
title: ToObject()
second_title: Aspose.Slides C++ API-referencia
description: Átalakítja a megadott 64 bites előjel nélküli egész értéket egy felsorolás elemévé.
type: docs
weight: 40
url: /hu/system/enumvaluesbase/toobject/
---
## EnumValuesBase::ToObject(const TypeInfo\&, uint64_t) metódus


Átalakítja a megadott 64 bites előjel nélküli egész értéket egy felsorolás elemévé.

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, uint64_t value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | A visszaadandó felsorolás típusa. |
| value | **uint64_t** | Az érték, amelyet a felsorolás elemévé kell konvertálni. |

### Visszatérési érték

A felsorolás egy példánya, amely az értékre van beállítva.

## EnumValuesBase::ToObject(const TypeInfo\&, const SharedPtr\<Object\>\&) metódus


Átalakítja a megadott objektumot, amely egész értékkel rendelkezik, egy felsorolás elemévé.

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, const SharedPtr<Object> &value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | A visszaadandó felsorolás típusa. |
| value | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Az érték, amely a felsorolás elemévé konvertálódik. |

### Visszatérési érték

Egy felsorolás objektum, amelynek az értéke a megadott érték.

## Lásd még

* Typedef [SharedPtr](../../sharedptr/)
* Osztály [Object](../../object/)
* Osztály [TypeInfo](../../typeinfo/)
* Osztály [EnumValuesBase](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)