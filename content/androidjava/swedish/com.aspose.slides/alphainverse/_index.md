---
title: AlphaInverse
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en Alpha Inverse-effekt.
type: docs
url: /sv/com.aspose.slides/alphainverse/
---
**Arv:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IAlphaInverse](../../com.aspose.slides/ialphainverse), com.aspose.slides.IVisualEffect
```
public final class AlphaInverse extends ImageTransformOperation implements IAlphaInverse, IVisualEffect
```

Representerar en Alpha Inverse-effekt. Alpha-värden (opacitet) inverteras genom att subtrahera från 100 %.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getEffective()](#getEffective--) | Hämtar effektiva Alpha Inverse-effektsdata med ärftlighet tillämpad. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om den angivna [AlphaInverse](../../com.aspose.slides/alphainverse) är lika med den nuvarande [AlphaInverse](../../com.aspose.slides/alphainverse). |
| [hashCode()](#hashCode--) | Fungerar som en hashfunktion för en viss typ. |
### getEffective() {#getEffective--}
```
public final IAlphaInverseEffectiveData getEffective()
```


Hämtar effektiva Alpha Inverse-effektsdata med ärftlighet tillämpad.

**Returnerar:**
[IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata) - En [IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Skrivskyddad long.

**Returnerar:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestämmer om den angivna [AlphaInverse](../../com.aspose.slides/alphainverse) är lika med den nuvarande [AlphaInverse](../../com.aspose.slides/alphainverse).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Den [AlphaInverse](../../com.aspose.slides/alphainverse) att jämföra. |

**Returnerar:**
boolean - true om objekten är lika; annars false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Fungerar som en hashfunktion för en viss typ.

**Returnerar:**
int - En hashkod för det aktuella objektet.