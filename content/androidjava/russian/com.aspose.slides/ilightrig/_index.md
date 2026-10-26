---
title: ILightRig
second_title: Aspose.Slides for Android via Java API Reference
description: Represents LightRig.
type: docs
url: /ru/com.aspose.slides/ilightrig/
---```
public interface ILightRig
```

Представляет LightRig.
## Методы

| Метод | Описание |
| --- | --- |
| [getDirection()](#getDirection--) | Направление света. |
| [setDirection(int value)](#setDirection-int-) | Направление света. |
| [getLightType()](#getLightType--) | Представляет предустановленный свет справа, который можно применить к фигуре. |
| [setLightType(int value)](#setLightType-int-) | Представляет предустановленный свет справа, который можно применить к фигуре. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Вращение определяется с помощью координаты широты, координаты долготы и оборота вокруг оси в виде координат широты и долготы. |
| [getRotation()](#getRotation--) | Вращение определяется с помощью координаты широты, координаты долготы и оборота вокруг оси в виде координат широты и долготы. |
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
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getLightType() {#getLightType--}
```
public abstract int getLightType()
```


Представляет предустановленный свет справа, который можно применить к фигуре. Light rig представляет группу светильников, ориентированных определённым образом относительно 3D-сцены. Чтение/запись [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Возвращаемое значение:**
int
### setLightType(int value) {#setLightType-int-}
```
public abstract void setLightType(int value)
```


Представляет предустановленный свет справа, который можно применить к фигуре. Light rig представляет группу светильников, ориентированных определённым образом относительно 3D-сцены. Чтение/запись [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```


Вращение определяется с помощью координаты широты, координаты долготы и оборота вокруг оси в виде координат широты и долготы.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| latitude | float | Координата широты float |
| longitude | float | Координата долготы float |
| revolution | float | Координата оборота float |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


Вращение определяется с помощью координаты широты, координаты долготы и оборота вокруг оси в виде координат широты и долготы. первый элемент в возвращаемом массиве - широта, второй - долгота, третий - оборот.

**Возвращаемое значение:**
float[] - Координаты вращения как float[]