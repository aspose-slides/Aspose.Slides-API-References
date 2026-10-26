---
title: ICameraEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Неизменяемый объект, содержащий эффективные свойства камеры.
type: docs
url: /ru/com.aspose.slides/icameraeffectivedata/
---```
public interface ICameraEffectiveData
```

Неизменяемый объект, содержащий эффективные свойства камеры.

--------------------

Этот интерфейс используется как часть [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Методы

| Метод | Описание |
| --- | --- |
| [getCameraType()](#getCameraType--) | Тип камеры. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Поле зрения камеры (0-180 deg, поле обзора). |
| [getZoom()](#getZoom--) | Масштаб камеры (положительное значение в процентах). |
| [getRotation()](#getRotation--) | Поворот определяется использованием координаты широты, координаты долготы и вращением вокруг оси, соответствующим этим координатам. первый элемент в возвращаемом массиве — широта, второй — долгота, третий — оборот. Возвращает null, если поворот не задан. |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

Тип камеры. Только для чтения [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Возвращает:**
int
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

Поле зрения камеры (0-180 deg, поле обзора). Только для чтения float.

**Возвращает:**
float
### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

Масштаб камеры (положительное значение в процентах). Только для чтения float.

**Возвращает:**
float
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Поворот определяется использованием координаты широты, координаты долготы и вращением вокруг оси, соответствующим этим координатам. первый элемент в возвращаемом массиве — широта, второй — долгота, третий — оборот. Возвращает null, если поворот не задан.

**Возвращает:**
float[] - Массив значений поворота в виде float[].