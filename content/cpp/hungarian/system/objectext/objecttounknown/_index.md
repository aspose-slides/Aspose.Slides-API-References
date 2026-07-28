---
title: ObjectToUnknown()
second_title: Aspose.Slides C++ API referencia
description: Átalakítja az Object-et ismeretlen típusra, kezelve mind az okos mutató típusú, mind a csomagolt értékhelyzeteket.
type: docs
weight: 131
url: /hu/system/objectext/objecttounknown/
---
## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) metódus


Átalakítja [Object](../../object/)-t ismeretlen típusra, kezelve mind a okos mutató típusú, mind a csomagolt értékhelyzeteket.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```


### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T | Az a típus, amelyre [Object](../../object/) átalakítható. |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | [Object](../../object/) átalakítandó. |

### Visszatérési érték

Vagy a csomagolatlan érték, vagy az átalakított mutató.

## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) metódus


Átalakítja [Object](../../object/)-t ismeretlen típusra, kezelve mind a okos mutató típusú, mind a csomagolt értékhelyzeteket.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```


### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T | Az a típus, amelyre [Object](../../object/) átalakítható. |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | [Object](../../object/) átalakítandó. |

### Visszatérési érték

Vagy a csomagolatlan érték, vagy az átalakított mutató.

## Lásd még

* Osztály [SmartPtr](../../smartptr/)
* Osztály [Object](../../object/)
* Osztály [ObjectExt](../)
* Struktúra [IsSmartPtr](../../issmartptr/)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)