---
title: HSL
second_title: Aspose.Slides för Java API-referens
description: Representerar en Hue/Saturation/Luminance-effekt.
type: docs
url: /sv/com.aspose.slides/hsl/
---
**Arv:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IHSL](../../com.aspose.slides/ihsl), com.aspose.slides.IVisualEffect
```
public final class HSL extends ImageTransformOperation implements IHSL, IVisualEffect
```

Representerar en Hue/Saturation/Luminance-effekt. Hue, Saturation och Luminance kan var och en justeras relativt till sitt nuvarande värde.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getEffective()](#getEffective--) | Hämtar effektiva Hue/Saturation/Luminance-effektdatat med arvet tillämpat. |
| [equals(Object obj)](#equals-java.lang.Object-) | Avgör om den angivna [HSL](../../com.aspose.slides/hsl) är lika med den aktuella [HSL](../../com.aspose.slides/hsl). |
| [hashCode()](#hashCode--) | Fungerar som en hash-funktion för en viss typ. |
### getEffective() {#getEffective--}
```
public final IHSLEffectiveData getEffective()
```

Hämtar effektiva Hue/Saturation/Luminance-effektdatat med arvet tillämpat.

**Returnerar:**
[IHSLEffectiveData](../../com.aspose.slides/ihsleffectivedata) - En [IHSLEffectiveData](../../com.aspose.slides/ihsleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Avgör om den angivna [HSL](../../com.aspose.slides/hsl) är lika med den aktuella [HSL](../../com.aspose.slides/hsl).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Den [HSL](../../com.aspose.slides/hsl) att jämföra. |

**Returnerar:**
boolean - true om objekten är lika; annars false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Fungerar som en hash-funktion för en viss typ.

**Returnerar:**
int - En hashkod för det aktuella objektet.