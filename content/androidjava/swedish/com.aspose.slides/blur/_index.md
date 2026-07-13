---
title: Blur
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en Blur-effekt som tillämpas på hela formen inklusive fyllningen.
type: docs
url: /sv/com.aspose.slides/blur/
---
**Arv:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IBlur](../../com.aspose.slides/iblur), com.aspose.slides.IVisualEffect
```
public final class Blur extends ImageTransformOperation implements IBlur, IVisualEffect
```

Representerar en Blur-effekt som tillämpas på hela formen, inklusive fyllningen. Alla färgkanaler, inklusive alfa, påverkas.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRadius()](#getRadius--) | Returnerar eller anger blur-radius. |
| [setRadius(double value)](#setRadius-double-) | Returnerar eller anger blur-radius. |
| [getGrow()](#getGrow--) | Bestämmer om objektets gränser ska utökas till följd av oskärpan. |
| [setGrow(boolean value)](#setGrow-boolean-) | Bestämmer om objektets gränser ska utökas till följd av oskärpan. |
| [getEffective()](#getEffective--) | Hämtar effektiva Blur-effektsdata med ärvd egenskap tillämpad. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om den angivna [Blur](../../com.aspose.slides/blur) är lika med den aktuella [Blur](../../com.aspose.slides/blur). |
| [hashCode()](#hashCode--) | Fungerar som en hash-funktion för en viss typ. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```

Returnerar eller anger blur-radius. Läs/skriv double.

**Returnerar:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

Returnerar eller anger blur-radius. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |
### getGrow() {#getGrow--}
```
public final boolean getGrow()
```

Bestämmer om objektets gränser ska utökas till följd av oskärpan. Sant innebär att gränserna utökas medan falskt innebär att de inte gör det. Läs/skriv boolean.

**Returnerar:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public final void setGrow(boolean value)
```

Bestämmer om objektets gränser ska utökas till följd av oskärpan. Sant innebär att gränserna utökas medan falskt innebär att de inte gör det. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getEffective() {#getEffective--}
```
public final IBlurEffectiveData getEffective()
```

Hämtar effektiva Blur-effektsdata med ärvd egenskap tillämpad.

**Returnerar:**
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata) - En [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Bestämmer om den angivna [Blur](../../com.aspose.slides/blur) är lika med den aktuella [Blur](../../com.aspose.slides/blur).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Det [Blur](../../com.aspose.slides/blur) att jämföra. |

**Returnerar:**
boolean - sant om objekten är lika; annars falskt.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Fungerar som en hash-funktion för en viss typ.

**Returnerar:**
int - En hash-kod för det aktuella objektet.