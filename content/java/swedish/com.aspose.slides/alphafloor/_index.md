---
title: AlphaFloor
second_title: Aspose.Slides för Java API-referens
description: Representerar en Alpha Floor-effekt.
type: docs
url: /sv/com.aspose.slides/alphafloor/
---
**Arv:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IAlphaFloor](../../com.aspose.slides/ialphafloor), com.aspose.slides.IVisualEffect
```
public final class AlphaFloor extends ImageTransformOperation implements IAlphaFloor, IVisualEffect
```

Representerar en Alpha Floor-effekt. Alpha (opacitet)-värden mindre än 100% ändras till noll. Med andra ord blir allt delvis transparent helt transparent.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getEffective()](#getEffective--) | Hämtar effektiv Alpha Floor-effektsdata med ärvda inställningar tillämpade. |
| [equals(Object obj)](#equals-java.lang.Object-) | Avgör om den angivna [AlphaFloor](../../com.aspose.slides/alphafloor) är lika med den aktuella [AlphaFloor](../../com.aspose.slides/alphafloor). |
| [hashCode()](#hashCode--) | Fungerar som en hash-funktion för en viss typ. |
### getEffective() {#getEffective--}
```
public final IAlphaFloorEffectiveData getEffective()
```


Hämtar effektiv Alpha Floor-effektsdata med ärvda inställningar tillämpade.

**Returnerar:**
[IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata) - en [IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Avgör om den angivna [AlphaFloor](../../com.aspose.slides/alphafloor) är lika med den aktuella [AlphaFloor](../../com.aspose.slides/alphafloor).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Den [AlphaFloor](../../com.aspose.slides/alphafloor) att jämföra. |

**Returnerar:**
boolean - true om objekten är lika; annars false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Fungerar som en hash-funktion för en viss typ.

**Returnerar:**
int - En hashkod för det aktuella objektet.