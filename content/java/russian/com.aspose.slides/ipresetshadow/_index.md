---
title: IPresetShadow
second_title: Справочник API Aspose.Slides для Java
description: Представляет предустановленный эффект тени.
type: docs
url: /ru/com.aspose.slides/ippresetshadow/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IPresetShadow extends IImageTransformOperation, IAccessiblePVIObject<IPresetShadowEffectiveData>
```

Представляет предустановленный эффект тени.
## Методы

| Метод | Описание |
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

**Возвращаемое значение:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

Направление тени. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

Расстояние тени. Чтение/запись double.

**Возвращаемое значение:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

Расстояние тени. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

Цвет тени. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращаемое значение:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public abstract int getPreset()
```

Предустановка. Чтение/запись [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Возвращаемое значение:**
int
### setPreset(int value) {#setPreset-int-}
```
public abstract void setPreset(int value)
```

Предустановка. Чтение/запись [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |