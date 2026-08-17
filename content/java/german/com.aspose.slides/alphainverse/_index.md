---
title: AlphaInverse
second_title: Aspose.Slides für Java API Referenz
description: Stellt einen Alpha Inverse-Effekt dar.
type: docs
url: /de/com.aspose.slides/alphainverse/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IAlphaInverse](../../com.aspose.slides/ialphainverse), com.aspose.slides.IVisualEffect
```
public final class AlphaInverse extends ImageTransformOperation implements IAlphaInverse, IVisualEffect
```

Stellt einen Alpha Inverse-Effekt dar. Alpha (opacity)-Werte werden invertiert, indem sie von 100 % subtrahiert werden.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getEffective()](#getEffective--) | Gets effective Alpha Inverse effect data with the inheritance applied. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [AlphaInverse](../../com.aspose.slides/alphainverse) is equal to the current [AlphaInverse](../../com.aspose.slides/alphainverse). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### getEffective() {#getEffective--}
```
public final IAlphaInverseEffectiveData getEffective()
```

Ermittelt effektive Alpha Inverse-Effektdaten unter Berücksichtigung der Vererbung.

**Rückgabewert:**
[IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata) - Ein [IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Nur lesbarer long.

**Rückgabewert:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Bestimmt, ob das angegebene [AlphaInverse](../../com.aspose.slides/alphainverse) gleich dem aktuellen [AlphaInverse](../../com.aspose.slides/alphainverse) ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Der [AlphaInverse](../../com.aspose.slides/alphainverse) zum Vergleich. |

**Rückgabewert:**
boolean - true, wenn Objekte gleich sind; andernfalls false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Dient als Hashfunktion für einen bestimmten Typ.

**Rückgabewert:**
int - Ein Hashcode für das aktuelle Objekt.