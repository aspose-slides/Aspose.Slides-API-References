---
title: GrayScale
second_title: Aspose.Slides Java API-referencia
description: Gray Scale effektet ábrázol.
type: docs
url: /hu/com.aspose.slides/grayscale/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**
[com.aspose.slides.IGrayScale](../../com.aspose.slides/igrayscale), com.aspose.slides.IVisualEffect
```
public final class GrayScale extends ImageTransformOperation implements IGrayScale, IVisualEffect
```

Gray Scale effektet ábrázol. Az összes effekt színértéket szürkeárnyalatba konvertálja, amely a luminanciájuknak felel meg. Az effekt alfa (átlátszóság) értékei változatlanok.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getEffective()](#getEffective--) | A származtatással alkalmazott hatékony Gray Scale effekt adatait kéri le. |
| [equals(Object obj)](#equals-java.lang.Object-) | Megállapítja, hogy a megadott [GrayScale](../../com.aspose.slides/grayscale) egyenlő-e a jelenlegi [GrayScale](../../com.aspose.slides/grayscale)-vel. |
| [hashCode()](#hashCode--) | Hash függvényként szolgál egy adott típushoz. |
### getEffective() {#getEffective--}
```
public final IGrayScaleEffectiveData getEffective()
```


A származtatással alkalmazott hatékony Gray Scale effekt adatait adja vissza.

**Visszatérési érték:**
[IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata) - A [IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Megállapítja, hogy a megadott [GrayScale](../../com.aspose.slides/grayscale) egyenlő-e a jelenlegi [GrayScale](../../com.aspose.slides/grayscale)-val.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | The [GrayScale](../../com.aspose.slides/grayscale) to compare. |

**Visszatérési érték:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hash függvényként szolgál egy adott típushoz.

**Visszatérési érték:**
int - A hash code for the current object.