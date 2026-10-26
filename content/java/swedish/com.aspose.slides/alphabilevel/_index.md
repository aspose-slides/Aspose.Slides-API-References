---
title: AlphaBiLevel
second_title: Aspose.Slides för Java API-referens
description: Representerar en Alpha Bi-Level-effekt.
type: docs
url: /sv/com.aspose.slides/alphabilevel/
---
**Arv:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IAlphaBiLevel](../../com.aspose.slides/ialphabilevel), com.aspose.slides.IVisualEffect
```
public final class AlphaBiLevel extends ImageTransformOperation implements IAlphaBiLevel, IVisualEffect
```

Representerar en Alpha Bi-Level-effekt. Alpha (Opacity)-värden som är mindre än tröskeln ändras till 0 (fullt transparent) och alfa-värden som är större än eller lika med tröskeln ändras till 100 % (fullt opak).
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getThreshold()](#getThreshold--) | Returnerar effekttröskel. |
| [setThreshold(float value)](#setThreshold-float-) | Returnerar effekttröskel. |
| [getEffective()](#getEffective--) | Hämtar effektiv Alpha Bi-Level-effektdatan med ärftligheten tillämpad. |
| [equals(Object obj)](#equals-java.lang.Object-) | Avgör om den angivna [AlphaBiLevel](../../com.aspose.slides/alphabilevel) är lika med den aktuella [AlphaBiLevel](../../com.aspose.slides/alphabilevel). |
| [hashCode()](#hashCode--) | Fungerar som en hashfunktion för en viss typ. |
### getThreshold() {#getThreshold--}
```
public final float getThreshold()
```


Returnerar effekttröskel. Läs/skriv float.

**Returnerar:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public final void setThreshold(float value)
```


Returnerar effekttröskel. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final IAlphaBiLevelEffectiveData getEffective()
```


Hämtar effektiv Alpha Bi-Level-effektdatan med ärftligheten tillämpad.

**Returnerar:**
[IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata) - En [IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Avgör om den angivna [AlphaBiLevel](../../com.aspose.slides/alphabilevel) är lika med den aktuella [AlphaBiLevel](../../com.aspose.slides/alphabilevel).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Det [AlphaBiLevel](../../com.aspose.slides/alphabilevel) att jämföra. |

**Returnerar:**
boolean - true om objekten är lika; annars false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Fungerar som en hashfunktion för en viss typ.

**Returnerar:**
int - En hashkod för det aktuella objektet.