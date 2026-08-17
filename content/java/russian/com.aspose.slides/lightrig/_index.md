---
title: LightRig
second_title: Справочник API Aspose.Slides для Java
description: Представляет LightRig.
type: docs
url: /ru/com.aspose.slides/lightrig/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Все реализованные интерфейсы:**
[com.aspose.slides.ILightRig](../../com.aspose.slides/ilightrig)
```
public final class LightRig extends PVIObject implements ILightRig
```

Представляет LightRig.
## Методы

| Метод | Описание |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDirection()](#getDirection--) | Направление света. |
| [setDirection(int value)](#setDirection-int-) | Направление света. |
| [getLightType()](#getLightType--) | Представляет предустановленный правый свет, который может быть применён к shape. |
| [setLightType(int value)](#setLightType-int-) | Представляет предустановленный правый свет, который может быть применён к shape. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Поворот определяется с помощью координаты широты, координаты долготы и вращения вокруг оси, соответствующего координатам широты и долготы. |
| [getRotation()](#getRotation--) | Поворот определяется с помощью координаты широты, координаты долготы и вращения вокруг оси, соответствующего координатам широты и долготы. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Версия. Только для чтения long.

**Возвращает:**
long
### getDirection() {#getDirection--}
```
public final int getDirection()
```

Направление света. Чтение/запись [LightingDirection](../../com.aspose.slides/lightingdirection).

**Возвращает:**
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```

Направление света. Чтение/запись [LightingDirection](../../com.aspose.slides/lightingdirection).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getLightType() {#getLightType--}
```
public final int getLightType()
```

Представляет предустановленный правый свет, который может быть применён к shape. LightRig представляет группу светильников, ориентированных определённым образом относительно 3D scene. Чтение/запись [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Возвращает:**
int
### setLightType(int value) {#setLightType-int-}
```
public final void setLightType(int value)
```

Представляет предустановленный правый свет, который может быть применён к shape. LightRig представляет группу светильников, ориентированных определённым образом относительно 3D scene. Чтение/запись [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

Поворот определяется с помощью координаты широты, координаты долготы и вращения вокруг оси, соответствующего координатам широты и долготы. Если любое значение координаты равно Float.NaN, весь поворот считается не определённым.

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

Поворот определяется с помощью координаты широты, координаты долготы и вращения вокруг оси, соответствующего координатам широты и долготы. Первый элемент в возвращаемом массиве — широта, второй — долгота, третий — вращение. Возвращает null, если поворот не определён.

**Возвращает:**
float[]