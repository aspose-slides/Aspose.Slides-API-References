---
title: GrayScale
second_title: Aspose.Slides für Java API-Referenz
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

Stellt einen Graustufen-Effekt dar. Konvertiert alle Effektfarbwerte in einen Grauton, der ihrer Leuchtkraft entspricht. Effekt-Alpha-(Opazität-)Werte bleiben unverändert.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getEffective()](#getEffective--) | Ruft die wirksamen Graustufen-Effektdaten ab, wobei die Vererbung angewendet wird. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene [GrayScale](../../com.aspose.slides/grayscale) dem aktuellen [GrayScale](../../com.aspose.slides/grayscale) entspricht. |
| [hashCode()](#hashCode--) | Dient als Hash-Funktion für einen bestimmten Typ. |
### getEffective() {#getEffective--}
```
public final IGrayScaleEffectiveData getEffective()
```

Ruft die wirksamen Graustufen-Effektdaten ab, wobei die Vererbung angewendet wird.

**Rückgabe:**
[IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata) - A [IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Bestimmt, ob das angegebene [GrayScale](../../com.aspose.slides/grayscale) dem aktuellen [GrayScale](../../com.aspose.slides/grayscale) entspricht.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das [GrayScale](../../com.aspose.slides/grayscale) zum Vergleich. |

**Rückgabe:**
boolean - true, wenn die Objekte gleich sind; andernfalls false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Dient als Hash-Funktion für einen bestimmten Typ.

**Rückgabe:**
int - ein Hash-Code für das aktuelle Objekt.