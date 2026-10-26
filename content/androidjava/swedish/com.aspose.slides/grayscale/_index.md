---
title: GrayScale
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en gråskalaeffekt.
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

Representerar en gråskalaeffekt. Konverterar alla effektfärgvärden till en nyans av grått, motsvarande deras luminans. Effektens alfa (opacitet) värden påverkas inte.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getEffective()](#getEffective--) | Hämtar effektiv Gray Scale-effektdata med ärftligheten tillämpad. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om den angivna [GrayScale](../../com.aspose.slides/grayscale) är lika med den aktuella [GrayScale](../../com.aspose.slides/grayscale). |
| [hashCode()](#hashCode--) | Fungerar som en hashfunktion för en viss typ. |
### getEffective() {#getEffective--}
```
public final IGrayScaleEffectiveData getEffective()
```


Hämtar effektiv Gray Scale-effektdata med ärftligheten tillämpad.

**Returnerar:**
[IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata) - En [IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestämmer om den angivna [GrayScale](../../com.aspose.slides/grayscale) är lika med den aktuella [GrayScale](../../com.aspose.slides/grayscale).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Den [GrayScale](../../com.aspose.slides/grayscale) att jämföra. |

**Returnerar:**
boolean - true om objekten är lika; annars false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Fungerar som en hashfunktion för en viss typ.

**Returnerar:**
int - En hashkod för det aktuella objektet.