---
title: IPresetShadow
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: Előre definiált árnyékhatást képvisel.
type: docs
url: /hu/com.aspose.slides/ippresetshadow/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IPresetShadow extends IImageTransformOperation, IAccessiblePVIObject<IPresetShadowEffectiveData>
```

Egy előre definiált árnyékhatást képvisel.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getDirection()](#getDirection--) | Árnyék iránya. |
| [setDirection(float value)](#setDirection-float-) | Árnyék iránya. |
| [getDistance()](#getDistance--) | Árnyék távolsága. |
| [setDistance(double value)](#setDistance-double-) | Árnyék távolsága. |
| [getShadowColor()](#getShadowColor--) | Árnyék színe. |
| [getPreset()](#getPreset--) | Előbeállítás. |
| [setPreset(int value)](#setPreset-int-) | Előbeállítás. |

### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

Árnyék iránya. Olvasás/írás float.

**Visszatér:**
float

### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

Árnyék iránya. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

Árnyék távolsága. Olvasás/írás double.

**Visszatér:**
double

### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

Árnyék távolsága. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

Árnyék színe. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatér:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getPreset() {#getPreset--}
```
public abstract int getPreset()
```

Előbeállítás. Olvasás/írás [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Visszatér:**
int

### setPreset(int value) {#setPreset-int-}
```
public abstract void setPreset(int value)
```

Előbeállítás. Olvasás/írás [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |