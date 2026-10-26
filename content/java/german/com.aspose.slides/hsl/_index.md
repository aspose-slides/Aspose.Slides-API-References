---
title: HSL
second_title: Aspose.Slides für Java API Referenz
description: Stellt einen Hue/Saturation/Luminance-Effekt dar.
type: docs
url: /de/com.aspose.slides/hsl/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IHSL](../../com.aspose.slides/ihsl), com.aspose.slides.IVisualEffect
```
public final class HSL extends ImageTransformOperation implements IHSL, IVisualEffect
```

Stellt einen Hue/Saturation/Luminance-Effekt dar. Der Farbton, die Sättigung und die Leuchtkraft können jeweils relativ zu ihrem aktuellen Wert angepasst werden.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getEffective()](#getEffective--) | Ruft die effektiven Hue/Saturation/Luminance-Effekt-Daten ab, wobei die Vererbung angewendet wird. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene [HSL](../../com.aspose.slides/hsl) dem aktuellen [HSL](../../com.aspose.slides/hsl) entspricht. |
| [hashCode()](#hashCode--) | Dient als Hash-Funktion für einen bestimmten Typ. |

### getEffective() {#getEffective--}
```
public final IHSLEffectiveData getEffective()
```

Ruft die effektiven Hue/Saturation/Luminance-Effekt-Daten ab, wobei die Vererbung angewendet wird.

**Rückgabewert:**
[IHSLEffectiveData](../../com.aspose.slides/ihsleffectivedata) - A [IHSLEffectiveData](../../com.aspose.slides/ihsleffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Bestimmt, ob das angegebene [HSL](../../com.aspose.slides/hsl) dem aktuellen [HSL](../../com.aspose.slides/hsl) entspricht.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das [HSL](../../com.aspose.slides/hsl) zum Vergleich. |

**Rückgabewert:**
boolean - true, wenn die Objekte gleich sind; andernfalls false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Dient als Hash-Funktion für einen bestimmten Typ.

**Rückgabewert:**
int - Ein Hash-Code für das aktuelle Objekt.