---
title: ICameraEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
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
| [getCameraType()](#getCameraType--) | Camera type. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Camera FOV (0-180 deg, field of View). |
| [getZoom()](#getZoom--) | Camera zoom (positive value in percentage). |
| [getRotation()](#getRotation--) | A rotation is defined through the use of a latitude coordinate, a longitude coordinate, and a revolution about the axis as the latitude and longitude coordinates. |
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

Поле зрения камеры (0-180 deg, field of View). Только для чтения float.

**Возвращает:**
float
### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

Увеличение камеры (положительное значение в процентах). Только для чтения float.

**Возвращает:**
float
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Вращение определяется с помощью координаты широты, координаты долготы и оборота вокруг оси как координаты широты и долготы. первый элемент возвращаемого массива — широта, второй — долгота, третий — оборот. Возвращает null, если вращение не определено.

**Возвращает:**
float[] - массив значений вращения в виде float[].