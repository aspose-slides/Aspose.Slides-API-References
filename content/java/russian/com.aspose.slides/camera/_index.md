---
title: Camera
second_title: Справочник API Aspose.Slides для Java
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
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Поле зрения камеры (0-180 градусов, поле зрения). |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | Поле зрения камеры (0-180 градусов, поле зрения). |
| [getZoom()](#getZoom--) | Масштаб камеры (положительное значение в процентах). |
| [setZoom(float value)](#setZoom-float-) | Масштаб камеры (положительное значение в процентах). |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Вращение определяется использованием координаты широты, координаты долготы и оборота вокруг оси в виде координат широты и долготы. |
| [getRotation()](#getRotation--) | Вращение определяется использованием координаты широты, координаты долготы и оборота вокруг оси в виде координат широты и долготы. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Версия. Только для чтения, тип long.

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

Поле зрения камеры (0-180 градусов, поле зрения). Чтение/запись float.

**Возвращаемое значение:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public final void setFieldOfViewAngle(float value)
```

Поле зрения камеры (0-180 градусов, поле зрения). Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |
### getZoom() {#getZoom--}
```
public final float getZoom()
```

Масштаб камеры (положительное значение в процентах). Чтение/запись float.

**Возвращаемое значение:**
float
### setZoom(float value) {#setZoom-float-}
```
public final void setZoom(float value)
```

Масштаб камеры (положительное значение в процентах). Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

Вращение определяется использованием координаты широты, координаты долготы и оборота вокруг оси в виде координат широты и долготы. Если любое значение координаты равно Float.NaN, всё вращение считается неопределённым.

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

Вращение определяется использованием координаты широты, координаты долготы и оборота вокруг оси в виде координат широты и долготы. Первый элемент возвращаемого массива — широта, второй — долгота, третий — оборот. Возвращает null, если вращение не определено.

**Возвращаемое значение:**
float[]