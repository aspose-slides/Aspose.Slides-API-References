---
title: LightRig
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет LightRig.
type: docs
url: /ru/com.aspose.slides/lightrig/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.ILightRig](../../com.aspose.slides/ilightrig)
```
public final class LightRig extends PVIObject implements ILightRig
```

Представляет LightRig.
## Методы

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDirection()](#getDirection--) | Направление света. |
| [setDirection(int value)](#setDirection-int-) | Направление света. |
| [getLightType()](#getLightType--) | Представляет предустановленный правый свет, который может быть применён к фигуре. |
| [setLightType(int value)](#setLightType-int-) | Представляет предустановленный правый свет, который может быть применён к фигуре. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Вращение определяется использованием координаты широты, координаты долготы и оборота вокруг оси, как координат широты и долготы. |
| [getRotation()](#getRotation--) | Вращение определяется использованием координаты широты, координаты долготы и оборота вокруг оси, как координат широты и долготы. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Версия. Только для чтения long.

**Возвращаемое значение:**
long
### getDirection() {#getDirection--}
```
public final int getDirection()
```

Направление света. Чтение/запись [LightingDirection](../../com.aspose.slides/lightingdirection).

**Возвращаемое значение:**
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```

Направление света. Чтение/запись [LightingDirection](../../com.aspose.slides/lightingdirection).

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getLightType() {#getLightType--}
```
public final int getLightType()
```

Представляет предустановленный правый свет, который может быть применён к фигуре. Light rig представляет группу светов, ориентированных определённым образом относительно 3D-сцены. Чтение/запись [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Возвращаемое значение:**
int
### setLightType(int value) {#setLightType-int-}
```
public final void setLightType(int value)
```

Представляет предустановленный правый свет, который может быть применён к фигуре. Light rig представляет группу светов, ориентированных определённым образом относительно 3D-сцены. Чтение/запись [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

Вращение определяется использованием координаты широты, координаты долготы и оборота вокруг оси, как координат широты и долготы. Если значение любой координаты равно Float.NaN, всё вращение считается неопределённым.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |
### getRotation() {#getRotation--}
```
public final float[] getRotation()
```

Вращение определяется использованием координаты широты, координаты долготы и оборота вокруг оси, как координат широты и долготы. Первый элемент возвращаемого массива — широта, второй — долгота, третий — оборот. Возвращает null, если вращение не определено.

**Возвращаемое значение:**
float[]