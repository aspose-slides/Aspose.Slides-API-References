---
title: ILightRig
second_title: Aspose.Slides for Java API Reference
description: Represents LightRig.
type: docs
url: /ru/com.aspose.slides/ilightrig/
---```
public interface ILightRig
```

Представляет LightRig.
## Методы

| Method | Description |
| --- | --- |
| [getDirection()](#getDirection--) | Направление света. |
| [setDirection(int value)](#setDirection-int-) | Направление света. |
| [getLightType()](#getLightType--) | Представляет предустановленный свет, который можно применить к фигуре. |
| [setLightType(int value)](#setLightType-int-) | Представляет предустановленный свет, который можно применить к фигуре. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Поворот определяется использованием координаты широты, координаты долготы и вращения вокруг оси как координат широты и долготы. |
| [getRotation()](#getRotation--) | Поворот определяется использованием координаты широты, координаты долготы и вращения вокруг оси как координат широты и долготы. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```


Направление света. Чтение/запись [LightingDirection](../../com.aspose.slides/lightingdirection).

**Возвращаемое значение:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```


Направление света. Чтение/запись [LightingDirection](../../com.aspose.slides/lightingdirection).

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getLightType() {#getLightType--}
```
public abstract int getLightType()
```


Представляет предустановленный свет, который можно применить к фигуре. Световая система представляет группу светильников, ориентированных определённым образом относительно 3D-сцены. Чтение/запись [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Возвращаемое значение:**
int
### setLightType(int value) {#setLightType-int-}
```
public abstract void setLightType(int value)
```


Представляет предустановленный свет, который можно применить к фигуре. Световая система представляет группу светильников, ориентированных определённым образом относительно 3D-сцены. Чтение/запись [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```


Поворот определяется использованием координаты широты, координаты долготы и вращения вокруг оси как координат широты и долготы.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| latitude | float | Координата широты float |
| longitude | float | Координата долготы float |
| revolution | float | Координата вращения float |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


Поворот определяется использованием координаты широты, координаты долготы и вращения вокруг оси как координат широты и долготы. Первый элемент в возвращаемом массиве — широта, второй — долгота, третий — вращение.

**Возвращаемое значение:**
float[] - Координаты вращения как float[]