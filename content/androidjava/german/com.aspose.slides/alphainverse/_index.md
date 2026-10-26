---
title: AlphaInverse
second_title: Aspose.Slides für Android über die Java API Referenz
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

Stellt einen Alpha Inverse-Effekt dar. Alpha (Opazität) Werte werden durch Subtraktion von 100 % invertiert.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getEffective()](#getEffective--) | Erhält die wirksamen Alpha Inverse-Effektdaten mit angewandter Vererbung. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene [AlphaInverse](../../com.aspose.slides/alphainverse) dem aktuellen [AlphaInverse](../../com.aspose.slides/alphainverse) entspricht. |
| [hashCode()](#hashCode--) | Dient als Hashfunktion für einen bestimmten Typ. |
### getEffective() {#getEffective--}
```
public final IAlphaInverseEffectiveData getEffective()
```


Erhält die wirksamen Alpha Inverse-Effektdaten mit angewandter Vererbung.

**Rückgabe:**
[IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata) - Ein [IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Nur-Lese long.

**Rückgabe:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob das angegebene [AlphaInverse](../../com.aspose.slides/alphainverse) dem aktuellen [AlphaInverse](../../com.aspose.slides/alphainverse) entspricht.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das [AlphaInverse](../../com.aspose.slides/alphainverse) zum Vergleich. |

**Rückgabe:**
boolean - true, wenn Objekte gleich sind; andernfalls false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Dient als Hashfunktion für einen bestimmten Typ.

**Rückgabe:**
int - Ein Hashcode für das aktuelle Objekt.