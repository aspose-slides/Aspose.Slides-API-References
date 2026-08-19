---
title: AlphaCeiling
second_title: Aspose.Slides för Java API-referens
description: Representerar en Alpha Ceiling-effekt.
type: docs
url: /sv/com.aspose.slides/alphaceiling/
---
**Arv:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IAlphaCeiling](../../com.aspose.slides/ialphaceiling), com.aspose.slides.IVisualEffect
```
public final class AlphaCeiling extends ImageTransformOperation implements IAlphaCeiling, IVisualEffect
```

Representerar en Alpha Ceiling-effekt. Alpha (opacity)-värden som är större än noll ändras till 100%. Med andra ord blir allt delvis ogenomskinligt helt ogenomskinligt.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getEffective()](#getEffective--) | Hämtar effektiv Alpha Ceiling-effektdat med det ärvda tillämpat. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om den specificerade [AlphaCeiling](../../com.aspose.slides/alphaceiling) är lika med den aktuella [AlphaCeiling](../../com.aspose.slides/alphaceiling). |
| [hashCode()](#hashCode--) | Fungerar som en hash-funktion för en specifik typ. |
### getEffective() {#getEffective--}
```
public final IAlphaCeilingEffectiveData getEffective()
```

Hämtar effektiv Alpha Ceiling-effektdat med det ärvda tillämpat.

**Returnerar:**
[IAlphaCeilingEffectiveData](../../com.aspose.slides/ialphaceilingeffectivedata) - En [IAlphaCeilingEffectiveData](../../com.aspose.slides/ialphaceilingeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Bestämmer om den specificerade [AlphaCeiling](../../com.aspose.slides/alphaceiling) är lika med den aktuella [AlphaCeiling](../../com.aspose.slides/alphaceiling).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Den [AlphaCeiling](../../com.aspose.slides/alphaceiling) att jämföra. |

**Returnerar:**
boolean - true om objekten är lika; annars false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Fungerar som en hash-funktion för en specifik typ.

**Returnerar:**
int - En hashkod för det aktuella objektet.