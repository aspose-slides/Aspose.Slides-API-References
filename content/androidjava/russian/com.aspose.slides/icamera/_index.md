---
title: ICamera
second_title: Aspose.Slides for Android via Java API Reference
description: Represents Camera.
type: docs
url: /ru/com.aspose.slides/icamera/
---```
public interface ICamera
```

Представляет камеру.
## Методы

| Метод | Описание |
| --- | --- |
| [getCameraType()](#getCameraType--) | Тип камеры Чтение/запись [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [setCameraType(int value)](#setCameraType-int-) | Тип камеры Чтение/запись [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Угол обзора камеры (0-180 deg, field of View) Чтение/запись float. |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | Угол обзора камеры (0-180 deg, field of View) Чтение/запись float. |
| [getZoom()](#getZoom--) | Масштаб камеры (positive value in percentage) Чтение/запись float. |
| [setZoom(float value)](#setZoom-float-) | Масштаб камеры (positive value in percentage) Чтение/запись float. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Вращение определяется с помощью координаты широты, координаты долготы и оборота вокруг оси как координат широты и долготы. |
| [getRotation()](#getRotation--) | Вращение определяется с помощью координаты широты, координаты долготы и оборота вокруг оси как координат широты и долготы. |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```


Тип камеры Чтение/запись [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Возвращаемое значение:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public abstract void setCameraType(int value)
```


Тип камеры Чтение/запись [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```


Угол обзора камеры (0-180 deg, field of View) Чтение/запись float.

**Возвращаемое значение:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public abstract void setFieldOfViewAngle(float value)
```


Угол обзора камеры (0-180 deg, field of View) Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```


Масштаб камеры (positive value in percentage) Чтение/запись float.

**Возвращаемое значение:**
float
### setZoom(float value) {#setZoom-float-}
```
public abstract void setZoom(float value)
```


Масштаб камеры (positive value in percentage) Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```


Вращение определяется с помощью координаты широты, координаты долготы и оборота вокруг оси как координат широты и долготы. Если любое значение координаты равно Float.NaN, всё вращение считается неопределённым.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| latitude | float | Значение широты float |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


Вращение определяется с помощью координаты широты, координаты долготы и оборота вокруг оси как координат широты и долготы. первый элемент в возвращаемом массиве — широта, второй — долгота, третий — оборот. Возвращает null, если вращение не определено.

**Возвращаемое значение:**
float[] - Array of rotation values as float[].