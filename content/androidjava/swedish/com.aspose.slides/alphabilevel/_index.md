---
title: AlphaBiLevel
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en Alpha Bi-Level-effekt.
type: docs
url: /sv/com.aspose.slides/alphabilevel/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**
[com.aspose.slides.IAlphaBiLevel](../../com.aspose.slides/ialphabilevel), com.aspose.slides.IVisualEffect
```
public final class AlphaBiLevel extends ImageTransformOperation implements IAlphaBiLevel, IVisualEffect
```

Representerar en Alpha Bi-Level-effekt. Alpha (Opacitet)-värden som är mindre än tröskeln ändras till 0 (helt transparent) och alpha-värden som är större än eller lika med tröskeln ändras till 100 % (helt opak).
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getThreshold()](#getThreshold--) | Returnerar effekttröskelvärdet. |
| [setThreshold(float value)](#setThreshold-float-) | Returnerar effekttröskelvärdet. |
| [getEffective()](#getEffective--) | Hämtar effektiv Alpha Bi-Level-effektdata med arv tillämpat. |
| [equals(Object obj)](#equals-java.lang.Object-) | Avgör om den angivna [AlphaBiLevel](../../com.aspose.slides/alphabilevel) är lika med den aktuella [AlphaBiLevel](../../com.aspose.slides/alphabilevel). |
| [hashCode()](#hashCode--) | Fungerar som en hash-funktion för en viss typ. |
### getThreshold() {#getThreshold--}
```
public final float getThreshold()
```

Returnerar effekttröskelvärdet. Läs/skriv float.

**Returnerar:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public final void setThreshold(float value)
```

Returnerar effekttröskelvärdet. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final IAlphaBiLevelEffectiveData getEffective()
```

Hämtar effektiv Alpha Bi-Level-effektdata med arv tillämpat.

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

Fungerar som en hash-funktion för en viss typ.

**Returnerar:**
int - En hashkod för det aktuella objektet.