---
title: GrayScale
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: Gray Scale hatást képvisel.
type: docs
url: /hu/com.aspose.slides/grayscale/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Minden megvalósított interfész:**
[com.aspose.slides.IGrayScale](../../com.aspose.slides/igrayscale), com.aspose.slides.IVisualEffect
```
public final class GrayScale extends ImageTransformOperation implements IGrayScale, IVisualEffect
```

Képviseli a Gray Scale hatást. Az összes effektusszín-értéket egy szürke árnyalatra konvertálja, amely a fényerőnek megfelelő. Az effektus alfa (átlátszatlanság) értékei változatlanok.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getEffective()](#getEffective--) | Lekéri a hatékony Gray Scale hatás adatokat az öröklődés alkalmazásával. |
| [equals(Object obj)](#equals-java.lang.Object-) | Megállapítja, hogy a megadott [GrayScale](../../com.aspose.slides/grayscale) egyenlő-e a jelenlegi [GrayScale](../../com.aspose.slides/grayscale)-vel. |
| [hashCode()](#hashCode--) | Hash függvényként szolgál egy adott típushoz. |
### getEffective() {#getEffective--}
```
public final IGrayScaleEffectiveData getEffective()
```


Lekéri a hatékony Gray Scale hatás adatokat az öröklődés alkalmazásával.

**Visszatérési érték:**
[IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata) - A [IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Megállapítja, hogy a megadott [GrayScale](../../com.aspose.slides/grayscale) egyenlő-e a jelenlegi [GrayScale](../../com.aspose.slides/grayscale)-vel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | A [GrayScale](../../com.aspose.slides/grayscale) összehasonlításához. |

**Visszatérési érték:**
boolean - igaz, ha az objektumok egyenlőek; egyébként hamis.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hash függvényként szolgál egy adott típushoz.

**Visszatérési érték:**
int - A jelenlegi objektum hash kódja.