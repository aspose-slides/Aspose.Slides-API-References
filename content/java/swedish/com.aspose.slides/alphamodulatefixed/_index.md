---
title: AlphaModulateFixed
second_title: Aspose.Slides för Java API-referens
description: Representerar en Alpha Modulate Fixed-effekt.
type: docs
url: /sv/com.aspose.slides/alphamodulatefixed/
---
**Arv:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed), com.aspose.slides.IVisualEffect
```
public final class AlphaModulateFixed extends ImageTransformOperation implements IAlphaModulateFixed, IVisualEffect
```

Representerar en Alpha Modulate Fixed-effekt. Effektens alfa (opacitet) värden multipliceras med en fast procentandel.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAmount()](#getAmount--) | Returnerar mängden effekt i procent. |
| [setAmount(float value)](#setAmount-float-) | Returnerar mängden effekt i procent. |
| [getEffective()](#getEffective--) | Hämtar effektiva Alpha Modulate Fixed-effektsdata med arv applicerat. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om den angivna [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed) är lika med det aktuella [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed). |
| [hashCode()](#hashCode--) | Fungerar som en hash-funktion för en viss typ. |

### getAmount() {#getAmount--}
```
public final float getAmount()
```

Returnerar mängden effekt i procent. Läs/skriv float.

**Returnerar:**
float

### setAmount(float value) {#setAmount-float-}
```
public final void setAmount(float value)
```

Returnerar mängden effekt i procent. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final IAlphaModulateFixedEffectiveData getEffective()
```

Hämtar effektiva Alpha Modulate Fixed-effektsdata med arv applicerat.

**Returnerar:**
[IAlphaModulateFixedEffectiveData](../../com.aspose.slides/ialphamodulatefixedeffectivedata) - En [IAlphaModulateFixedEffectiveData](../../com.aspose.slides/ialphamodulatefixedeffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Bestämmer om den angivna [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed) är lika med det aktuella [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Den [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed) att jämföra. |

**Returnerar:**
boolean - sant om objekten är lika; annars falskt.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Fungerar som en hash-funktion för en viss typ.

**Returnerar:**
int - En hashkod för det aktuella objektet.