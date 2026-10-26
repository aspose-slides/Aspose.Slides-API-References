---
title: AlphaInverse
second_title: Aspose.Slides för Java API-referens
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

Representerar en Alpha Inverse-effekt. Alpha (opacitet)-värden inverteras genom att subtrahera från 100%.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getEffective()](#getEffective--) | Hämtar effektiva Alpha Inverse-effektsdata med arv tillämpat. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Avgör om den angivna [AlphaInverse](../../com.aspose.slides/alphainverse) är lika med den aktuella [AlphaInverse](../../com.aspose.slides/alphainverse). |
| [hashCode()](#hashCode--) | Fungerar som en hashfunktion för en viss typ. |
### getEffective() {#getEffective--}
```
public final IAlphaInverseEffectiveData getEffective()
```


Hämtar effektiva Alpha Inverse-effektsdata med arv tillämpat.

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


Avgör om den angivna [AlphaInverse](../../com.aspose.slides/alphainverse) är lika med den aktuella [AlphaInverse](../../com.aspose.slides/alphainverse).

**Parametrar:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Det [AlphaInverse](../../com.aspose.slides/alphainverse) som ska jämföras. |

**Returnerar:**
boolean - true om objekten är lika; annars false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Fungerar som en hashfunktion för en viss typ.

**Returnerar:**
int - En hashkod för det aktuella objektet.