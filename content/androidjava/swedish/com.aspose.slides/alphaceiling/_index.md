---
title: AlphaCeiling
second_title: Aspose.Slides för Android via Java API-referens
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

Representerar en Alpha Ceiling-effekt. Alpha-värden (opacitet) som är större än noll ändras till 100 %. Med andra ord blir allt som är delvis ogenomskinligt helt ogenomskinligt.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getEffective()](#getEffective--) | Hämtar effektiv Alpha Ceiling-effektsdata med ärftligheten tillämpad. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om den angivna [AlphaCeiling](../../com.aspose.slides/alphaceiling) är lika med den aktuella [AlphaCeiling](../../com.aspose.slides/alphaceiling). |
| [hashCode()](#hashCode--) | Fungerar som en hash-funktion för en viss typ. |

### getEffective() {#getEffective--}
```
public final IAlphaCeilingEffectiveData getEffective()
```

Hämtar effektiv Alpha Ceiling-effektsdata med ärftligheten tillämpad.

**Returnerar:**
[IAlphaCeilingEffectiveData](../../com.aspose.slides/ialphaceilingeffectivedata) - En [IAlphaCeilingEffectiveData](../../com.aspose.slides/ialphaceilingeffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Bestämmer om den angivna [AlphaCeiling](../../com.aspose.slides/alphaceiling) är lika med den aktuella [AlphaCeiling](../../com.aspose.slides/alphaceiling).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Den [AlphaCeiling](../../com.aspose.slides/alphaceiling) att jämföra. |

**Returnerar:**
boolean - sant om objekten är lika; annars falskt.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Fungerar som en hash-funktion för en viss typ.

**Returnerar:**
int - En hash-kod för det aktuella objektet.