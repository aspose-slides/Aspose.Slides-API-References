---
title: Luminance
second_title: Aspose.Slides Androidhoz Java API referencia
description: Luminancia hatást reprezentál.
type: docs
url: /hu/com.aspose.slides/luminance/
---
**Öröklődés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Minden megvalósított interfész:**
[com.aspose.slides.ILuminance](../../com.aspose.slides/iluminance), com.aspose.slides.IVisualEffect
```
public final class Luminance extends ImageTransformOperation implements ILuminance, IVisualEffect
```

Luminancia hatást reprezentál. A fényerő lineárisan minden színt közelebb hoz a fehér vagy a fekete felé. A kontraszt minden színt vagy közelebb, vagy távolabb helyez egymástól.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getEffective()](#getEffective--) | A öröklődés alkalmazásával lekéri a hatékony Luminancia hatás adatokat. |
| [equals(Object obj)](#equals-java.lang.Object-) | Megállapítja, hogy a megadott [Luminance](../../com.aspose.slides/luminance) egyenlő-e a jelenlegi [Luminance](../../com.aspose.slides/luminance). |
| [hashCode()](#hashCode--) | Hash függvényként szolgál egy adott típushoz. |
### getEffective() {#getEffective--}
```
public final ILuminanceEffectiveData getEffective()
```


A öröklődés alkalmazásával lekéri a hatékony Luminancia hatás adatokat.

**Visszatérési érték:**
[ILuminanceEffectiveData](../../com.aspose.slides/iluminanceeffectivedata) - Egy [ILuminanceEffectiveData](../../com.aspose.slides/iluminanceeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Megállapítja, hogy a megadott [Luminance](../../com.aspose.slides/luminance) egyenlő-e a jelenlegi [Luminance](../../com.aspose.slides/luminance).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | A [Luminance](../../com.aspose.slides/luminance) a összehasonlításhoz. |

**Visszatérési érték:**
boolean - igaz, ha az objektumok egyenlőek; egyébként hamis.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hash függvényként szolgál egy adott típushoz.

**Visszatérési érték:**
int - Egy hash kód a jelenlegi objektumhoz.