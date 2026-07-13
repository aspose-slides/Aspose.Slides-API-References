---
title: AlphaFloor
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en Alpha Floor-effekt.
type: docs
url: /sv/com.aspose.slides/alphafloor/
---
**Arv:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IAlphaFloor](../../com.aspose.slides/ialphafloor), com.aspose.slides.IVisualEffect
```
public final class AlphaFloor extends ImageTransformOperation implements IAlphaFloor, IVisualImpact
```

Representerar en Alpha Floor-effekt. Alpha-värden (opacitet) under 100 % ändras till noll. Med andra ord blir allt delvis genomskinligt helt genomskinligt.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getEffective()](#getEffective--) | Hämtar effektiva Alpha Floor-effektsdata med arv tillämpat. |
| [equals(Object obj)](#equals-java.lang.Object-) | Avgör om den angivna [AlphaFloor](../../com.aspose.slides/alphafloor) är lika med den aktuella [AlphaFloor](../../com.aspose.slides/alphafloor). |
| [hashCode()](#hashCode--) | Fungerar som en hashfunktion för en viss typ. |
### getEffective() {#getEffective--}
```
public final IAlphaFloorEffectiveData getEffective()
```


Hämtar effektiva Alpha Floor-effektsdata med arv tillämpat.

**Returnerar:**
[IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata) - En [IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Avgör om den angivna [AlphaFloor](../../com.aspose.slides/alphafloor) är lika med den aktuella [AlphaFloor](../../com.aspose.slides/alphafloor).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Det [AlphaFloor](../../com.aspose.slides/alphafloor) som ska jämföras. |

**Returnerar:**
boolean - true om objekten är lika; annars false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Fungerar som en hashfunktion för en viss typ.

**Returnerar:**
int - En hashkod för det aktuella objektet.