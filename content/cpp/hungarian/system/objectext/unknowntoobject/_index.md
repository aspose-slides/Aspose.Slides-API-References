---
title: UnknownToObject()
second_title: Aspose.Slides for C++ API hivatkozás
description: Átkonvertálja az ismeretlen típust az Object típusra, kezelve a smart pointer és értéktípus helyzeteket.
type: docs
weight: 118
url: /hu/system/objectext/unknowntoobject/
---
## ObjectExt::UnknownToObject(T) metódus


Átkonvertál egy ismeretlen típust a(z) [Object](../../object/) típusra, kezelve a smart pointer és értéktípus eseteket.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(T obj)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Az átkonvertálandó típus a(z) [Object](../../object/) típusra. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | T | [Object](../../object/) a konvertáláshoz. |

### Visszatérési érték

Smart pointer a(z) [Object](../../object/)-re, amely konvertált pointer vagy dobozolt érték.

## ObjectExt::UnknownToObject(const T\&) metódus


Átkonvertál egy ismeretlen típust a(z) [Object](../../object/) típusra, kezelve a smart pointer és értéktípus eseteket.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(const T &obj)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Az átkonvertálandó típus a(z) [Object](../../object/) típusra. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) a konvertáláshoz. |

### Visszatérési érték

Smart pointer a(z) [Object](../../object/)-re, amely konvertált pointer vagy dobozolt érték.

## Lásd még

* Osztály [SmartPtr](../../smartptr/)
* Osztály [Object](../../object/)
* Osztály [ObjectExt](../)
* Struktúra [IsSmartPtr](../../issmartptr/)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)