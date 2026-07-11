---
title: Camera
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет камеру.
type: docs
url: /ru/com.aspose.slides/camera/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Все реализованные интерфейсы:**
[com.aspose.slides.ICamera](../../com.aspose.slides/icamera)
```
public final class Camera extends PVIObject implements ICamera
```

Представляет камеру.
## Методы

| Метод | Описание |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getCameraType()](#getCameraType--) | Тип камеры. |
| [setCameraType(int value)](#setCameraType-int-) | Тип камеры. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Угол обзора камеры (0-180 deg, field of View). |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | Угол обзора камеры (0-180 deg, field of View). |
| [getZoom()](#getZoom--) | Зум камеры (положительное значение в процентах). |
| [setZoom(float value)](#setZoom-float-) | Зум камеры (положительное значение в процентах). |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Вращение определяется использованием координаты широты, координаты долготы и вращения вокруг оси как координат широты и долготы. |
| [getRotation()](#getRotation--) | Вращение определяется использованием координаты широты, координаты долготы и вращения вокруг оси как координат широты и долготы. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Версия. Только для чтения long.

**Возвращаемое значение:**
long
### getCameraType() {#getCameraType--}
```
public final int getCameraType()
```

Тип камеры. Чтение/запись [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Возвращаемое значение:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public final void setCameraType(int value)
```

Тип камеры. Чтение/запись [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public final float getFieldOfViewAngle()
```

Угол обзора камеры (0-180 deg, field of View). Чтение/запись float.

**Возвращаемое значение:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public final void setFieldOfViewAngle(float value)
```

Угол обзора камеры (0-180 deg, field of View). Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |
### getZoom() {#getZoom--}
```
public final float getZoom()
```

Зум камеры (положительное значение в процентах). Чтение/запись float.

**Возвращаемое значение:**
float
### setZoom(float value) {#setZoom-float-}
```
public final void setZoom(float value)
```

Зум камеры (положительное значение в процентах). Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

Вращение определяется использованием координаты широты, координаты долготы и вращения вокруг оси как координат широты и долготы. Если любое значение координаты равно Float.NaN, всё вращение не определено.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |
### getRotation() {#getRotation--}
```
public final float[] getRotation()
```

Вращение определяется использованием координаты широты, координаты долготы и вращения вокруг оси как координат широты и долготы. первый элемент возвращаемого массива — latitude, второй — longitude, третий — revolution. Возвращает null, если вращение не определено.

**Возвращаемое значение:**
float[]