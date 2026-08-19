---
title: GrayScale
second_title: Aspose.Slides för Java API-referens
description: Representerar en Gray Scale-effekt.
type: docs
url: /sv/com.aspose.slides/grayscale/
---
**Arv:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IGrayScale](../../com.aspose.slides/igrayscale), com.aspose.slides.IVisualEffect
```
public final class GrayScale extends ImageTransformOperation implements IGrayScale, IVisualEffect
```

Representerar en Gray Scale-effekt. Konverterar alla effektfärgvärden till en nyans av grått, motsvarande deras luminans. Effektens alpha (opacitet) värden påverkas inte.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getEffective()](#getEffective--) | Gets effective Gray Scale effect data with the inheritance applied. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [GrayScale](../../com.aspose.slides/grayscale) is equal to the current [GrayScale](../../com.aspose.slides/grayscale). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### getEffective() {#getEffective--}
```
public final IGrayScaleEffectiveData getEffective()
```


Hämtar effektiva Gray Scale-effektsdata med arv tillämpat.

**Returnerar:**
[IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata) - A [IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestämmer huruvida den angivna [GrayScale](../../com.aspose.slides/grayscale) är lika med den aktuella [GrayScale](../../com.aspose.slides/grayscale).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Den [GrayScale](../../com.aspose.slides/grayscale) att jämföra. |

**Returnerar:**
boolean - sant om objekten är lika; annars falskt.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Fungerar som en hash-funktion för en viss typ.

**Returnerar:**
int - En hashkod för det aktuella objektet.