---
title: IPresetShadow
second_title: Aspose.Slides для Android через Java API Reference
description: Представляет предустановленный эффект тени.
type: docs
url: /ru/com.aspose.slides/ippresetshadow/
---
**All Implemented Interfaces:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IPresetShadow extends IImageTransformOperation, IAccessiblePVIObject<IPresetShadowEffectiveData>
```

Представляет предустановленный эффект тени.
## Методы

| Method | Description |
| --- | --- |
| [getDirection()](#getDirection--) | Направление тени. |
| [setDirection(float value)](#setDirection-float-) | Направление тени. |
| [getDistance()](#getDistance--) | Расстояние тени. |
| [setDistance(double value)](#setDistance-double-) | Расстояние тени. |
| [getShadowColor()](#getShadowColor--) | Цвет тени. |
| [getPreset()](#getPreset--) | Предустановка. |
| [setPreset(int value)](#setPreset-int-) | Предустановка. |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```


Направление тени. Чтение/запись float.

**Returns:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```


Направление тени. Чтение/запись float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```


Расстояние тени. Чтение/запись double.

**Returns:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```


Расстояние тени. Чтение/запись double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```


Цвет тени. Только чтение [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public abstract int getPreset()
```


Предустановка. Чтение/запись [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Returns:**
int
### setPreset(int value) {#setPreset-int-}
```
public abstract void setPreset(int value)
```


Предустановка. Чтение/запись [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |