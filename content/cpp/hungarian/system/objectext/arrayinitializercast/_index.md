---
title: ArrayInitializerCast()
second_title: Aspose.Slides C++ API Referencia
description: Átalakítja a tömb alapvető értékeit (amelyet a C# implicit módon végez, de a C++ látszólag nem).
type: docs
weight: 209
url: /hu/system/objectext/arrayinitializercast/
---
## ObjectExt::ArrayInitializerCast(From ...) metódus


Átalakítja a tömb alapvető értékeit (amelyet a C# implicit módon végez, de a C++ látszólag nem).

```cpp
template<typename To,typename ...> static std::enable_if<(std::is_fundamental<To>::value), std::array<To, sizeof...(From)>>::type System::ObjectExt::ArrayInitializerCast(From ...args)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| To | Cél típus. |
| From | Forrás típusok. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| args | From ... | A konvertálandó és a cél tömbbe betolni kívánt értékek. |

### Visszatérési érték

[Array](../../array/) a tömben az összes argumentum átalakított másolatait ugyanabban a sorrendben tartalmazza.

## Lásd még

* Osztály [ObjectExt](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)