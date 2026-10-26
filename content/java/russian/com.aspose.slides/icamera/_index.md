---
title: ICamera
second_title: Aspose.Slides for Java API Reference
description: Представляет камеру.
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
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Поле зрения камеры (0-180 deg, field of View) Чтение/запись float. |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | Поле зрения камеры (0-180 deg, field of View) Чтение/запись float. |
| [getZoom()](#getZoom--) | Масштаб камеры (положительное значение в процентах) Чтение/запись float. |
| [setZoom(float value)](#setZoom-float-) | Масштаб камеры (положительное значение в процентах) Чтение/запись float. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Вращение определяется использованием координаты широты, координаты долготы и оборота вокруг оси в виде координат широты и долготы. |
| [getRotation()](#getRotation--) | Вращение определяется использованием координаты широты, координаты долготы и оборота вокруг оси в виде координат широты и долготы. |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```


Тип камеры Чтение/запись [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Возвращает:**
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


Поле зрения камеры (0-180 deg, field of View) Чтение/запись float.

**Возвращает:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public abstract void setFieldOfViewAngle(float value)
```


Поле зрения камеры (0-180 deg, field of View) Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```


Масштаб камеры (положительное значение в процентах) Чтение/запись float.

**Возвращает:**
float
### setZoom(float value) {#setZoom-float-}
```
public abstract void setZoom(float value)
```


Масштаб камеры (положительное значение в процентах) Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```


Вращение определяется использованием координаты широты, координаты долготы и оборота вокруг оси в виде координат широты и долготы. Если какое-либо значение координаты равно Float.NaN, всё вращение считается неопределённым.

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


Вращение определяется использованием координаты широты, координаты долготы и оборота вокруг оси в виде координат широты и долготы. первый элемент в возвращаемом массиве — широта, второй — долгота, третий — оборот. Возвращает null, если вращение не определено.

**Возвращает:**
float[] — массив значений вращения в виде float[].