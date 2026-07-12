---
title: GrayScale
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt einen Graustufen-Effekt dar.
type: docs
url: /de/com.aspose.slides/grayscale/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IGrayScale](../../com.aspose.slides/igrayscale), com.aspose.slides.IVisualEffect
```
public final class GrayScale extends ImageTransformOperation implements IGrayScale, IVisualEffect
```

Stellt einen Graustufen-Effekt dar. Konvertiert alle Effektfarbwerte in einen Grauton, der ihrer Leuchtkraft entspricht. Alpha-Werte (Deckkraft) des Effekts bleiben unverändert.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getEffective()](#getEffective--) | Ruft effektive Graustufen-Effektdaten mit angewandter Vererbung ab. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene [GrayScale](../../com.aspose.slides/grayscale) gleich dem aktuellen [GrayScale](../../com.aspose.slides/grayscale) ist. |
| [hashCode()](#hashCode--) | Dient als Hashfunktion für einen bestimmten Typ. |
### getEffective() {#getEffective--}
```
public final IGrayScaleEffectiveData getEffective()
```

Ruft effektive Graustufen-Effektdaten mit angewandter Vererbung ab.

**Rückgabe:**
[IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata) - Ein [IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Bestimmt, ob das angegebene [GrayScale](../../com.aspose.slides/grayscale) gleich dem aktuellen [GrayScale](../../com.aspose.slides/grayscale) ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Der [GrayScale](../../com.aspose.slides/grayscale) zum Vergleichen. |

**Rückgabe:**
boolean - true, wenn Objekte gleich sind; andernfalls false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Dient als Hashfunktion für einen bestimmten Typ.

**Rückgabe:**
int - Ein Hashcode für das aktuelle Objekt.