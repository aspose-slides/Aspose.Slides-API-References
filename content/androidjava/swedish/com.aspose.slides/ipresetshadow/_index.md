---
title: IPresetShadow
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en förinställd skuggeffekt.
type: docs
url: /sv/com.aspose.slides/ipresetshadow/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IPresetShadow extends IImageTransformOperation, IAccessiblePVIObject<IPresetShadowEffectiveData>
```

Representerar en förinställd skuggeffekt.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getDirection()](#getDirection--) | Skuggans riktning. |
| [setDirection(float value)](#setDirection-float-) | Skuggans riktning. |
| [getDistance()](#getDistance--) | Skuggans avstånd. |
| [setDistance(double value)](#setDistance-double-) | Skuggans avstånd. |
| [getShadowColor()](#getShadowColor--) | Skuggans färg. |
| [getPreset()](#getPreset--) | Förinställning. |
| [setPreset(int value)](#setPreset-int-) | Förinställning. |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

Skuggans riktning. Läs/skriv float.

**Returnerar:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

Skuggans riktning. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

Skuggans avstånd. Läs/skriv double.

**Returnerar:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

Skuggans avstånd. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

Skuggans färg. Endast läsbar [IColorFormat](../../com.aspose.slides/icolorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public abstract int getPreset()
```

Förinställning. Läs/skriv [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Returnerar:**
int
### setPreset(int value) {#setPreset-int-}
```
public abstract void setPreset(int value)
```

Förinställning. Läs/skriv [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |