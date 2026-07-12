---
title: ColorReplace
second_title: Aspose.Slides Androidra a Java API Referencián keresztül
description: Egy Color Replacement effektust reprezentál.
type: docs
url: /hu/com.aspose.slides/colorreplace/
---
**Öröklődés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Minden megvalósított interfész:**
[com.aspose.slides.IColorReplace](../../com.aspose.slides/icolorreplace), com.aspose.slides.IVisualEffect, java.lang.Cloneable
```
public final class ColorReplace extends ImageTransformOperation implements IColorReplace, IVisualEffect, Cloneable
```

Egy Color Replacement effektust reprezentál. Az összes effektusszín egy rögzített színre változik. Az alfa értékek változatlanok.

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getColor()](#getColor--) | Visszaadja a színformátumot, amely minden pixel színét helyettesíti. |
| [getEffective()](#getEffective--) | Lekéri a hatékony Color Replacement effekt adatot az öröklődés alkalmazásával. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Meghatározza, hogy a megadott [ColorReplace](../../com.aspose.slides/colorreplace) egyenlő-e a jelenlegi [ColorReplace](../../com.aspose.slides/colorreplace)-val. |
| [hashCode()](#hashCode--) | Hash függvényként szolgál egy adott típushoz. |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```


Visszaadja a színformátumot, amely minden pixel színét helyettesíti. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatér:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorReplaceEffectiveData getEffective()
```


Lekéri a hatékony Color Replacement effekt adatot az öröklődés alkalmazásával.

**Visszatér:**
[IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata) - A [IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Verzió. Csak olvasható long.

**Visszatér:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Meghatározza, hogy a megadott [ColorReplace](../../com.aspose.slides/colorreplace) egyenlő-e a jelenlegi [ColorReplace](../../com.aspose.slides/colorreplace)-val.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | A [ColorReplace](../../com.aspose.slides/colorreplace) a összehasonlításhoz. |

**Visszatér:**
boolean - true, ha az objektumok egyenlőek; egyébként false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hash függvényként szolgál egy adott típushoz.

**Visszatér:**
int - A hash kód a jelenlegi objektumhoz.