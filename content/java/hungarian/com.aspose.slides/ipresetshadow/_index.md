---
title: IPresetShadow
second_title: Aspose.Slides Java API referencia
description: Egy előre beállított árnyékhatást ábrázol.
type: docs
url: /hu/com.aspose.slides/ippresetshadow/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IPresetShadow extends IImageTransformOperation, IAccessiblePVIObject<IPresetShadowEffectiveData>
```

Egy előre beállított árnyékhatást ábrázol.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getDirection()](#getDirection--) | Direction of shadow. |
| [setDirection(float value)](#setDirection-float-) | Direction of shadow. |
| [getDistance()](#getDistance--) | Distance of shadow. |
| [setDistance(double value)](#setDistance-double-) | Distance of shadow. |
| [getShadowColor()](#getShadowColor--) | Color of shadow. |
| [getPreset()](#getPreset--) | Preset. |
| [setPreset(int value)](#setPreset-int-) | Preset. |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

Az árnyék iránya. Olvasás/írás float.

**Visszatér:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

Az árnyék iránya. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

Az árnyék távolsága. Olvasás/írás double.

**Visszatér:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

Az árnyék távolsága. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

Az árnyék színe. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatér:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public abstract int getPreset()
```

Előre beállított. Olvasás/írás [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Visszatér:**
int
### setPreset(int value) {#setPreset-int-}
```
public abstract void setPreset(int value)
```

Előre beállított. Olvasás/írás [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |