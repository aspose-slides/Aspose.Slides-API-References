---
title: AlphaModulate
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en Alpha Modulate-effekt.
type: docs
url: /sv/com.aspose.slides/alphamodulate/
---
**Arv:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IAlphaModulate](../../com.aspose.slides/ialphamodulate), com.aspose.slides.IVisualEffect
```
public final class AlphaModulate extends ImageTransformOperation implements IAlphaModulate, IVisualEffect
```

Representerar en Alpha Modulate-effekt. Effektens alfa (opacitet)-värden multipliceras med en fast procentsats. Effektbehållaren specificerar en effekt som innehåller alfa-värden att modulera.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getEffective()](#getEffective--) | Hämtar effektiva Alpha Modulate-effektdatan med arv tillämpat. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om den angivna [AlphaModulate](../../com.aspose.slides/alphamodulate) är lika med den aktuella [AlphaModulate](../../com.aspose.slides/alphamodulate). |
| [hashCode()](#hashCode--) | Fungerar som en hash-funktion för en viss typ. |
### getEffective() {#getEffective--}
```
public final IAlphaModulateEffectiveData getEffective()
```


Hämtar effektiva Alpha Modulate-effektdatan med arv tillämpat.

**Returnerar:**
[IAlphaModulateEffectiveData](../../com.aspose.slides/ialphamodulateeffectivedata) - En [IAlphaModulateEffectiveData](../../com.aspose.slides/ialphamodulateeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestämmer om den angivna [AlphaModulate](../../com.aspose.slides/alphamodulate) är lika med den aktuella [AlphaModulate](../../com.aspose.slides/alphamodulate).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Den [AlphaModulate](../../com.aspose.slides/alphamodulate) att jämföra. |

**Returnerar:**
boolean - true om objekten är lika; annars false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Fungerar som en hash-funktion för en viss typ.

**Returnerar:**
int - En hashkod för det aktuella objektet.