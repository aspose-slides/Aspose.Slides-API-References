---
title: Luminance
second_title: Aspose.Slides für Android über Java API Referenz
description: Stellt einen Luminance-Effekt dar.
type: docs
url: /de/com.aspose.slides/luminance/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ILuminance](../../com.aspose.slides/iluminance), com.aspose.slides.IVisualEffect
```
public final class Luminance extends ImageTransformOperation implements ILuminance, IVisualEffect
```

Stellt einen Luminance-Effekt dar. Die Helligkeit verschiebt alle Farben linear näher zu Weiß oder Schwarz. Der Kontrast skaliert alle Farben, sodass sie entweder näher beieinander oder weiter auseinander liegen.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getEffective()](#getEffective--) | Ermittelt wirksame Luminance-Effektdaten mit angewandter Vererbung. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene [Luminance](../../com.aspose.slides/luminance) dem aktuellen [Luminance](../../com.aspose.slides/luminance) entspricht. |
| [hashCode()](#hashCode--) | Dient als Hash-Funktion für einen bestimmten Typ. |

### getEffective() {#getEffective--}
```
public final ILuminanceEffectiveData getEffective()
```

Ermittelt wirksame Luminance-Effektdaten mit angewandter Vererbung.

**Rückgabewert:**
[ILuminanceEffectiveData](../../com.aspose.slides/iluminanceeffectivedata) - Ein [ILuminanceEffectiveData](../../com.aspose.slides/iluminanceeffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Bestimmt, ob das angegebene [Luminance](../../com.aspose.slides/luminance) dem aktuellen [Luminance](../../com.aspose.slides/luminance) entspricht.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das [Luminance](../../com.aspose.slides/luminance) zum Vergleich. |

**Rückgabewert:**
boolean - true, wenn Objekte gleich sind; andernfalls false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Dient als Hash-Funktion für einen bestimmten Typ.

**Rückgabewert:**
int - Ein Hash-Code für das aktuelle Objekt.