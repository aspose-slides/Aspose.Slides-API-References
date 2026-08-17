---
title: Backdrop3DScene
second_title: Справочник API Aspose.Slides для Java
description: Определяет плоскость, в которой такие эффекты, как свечение и тень, применяются относительно формы, к которой они применяются.
type: docs
url: /ru/com.aspose.slides/backdrop3dscene/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IBackdrop3DScene](../../com.aspose.slides/ibackdrop3dscene)
```
public final class Backdrop3DScene extends PVIObject implements IBackdrop3DScene
```

Определяет плоскость, в которой эффекты, такие как сияние и тень, применяются относительно формы, к которой они применяются.
## Методы

| Метод | Описание |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNormalVector()](#getNormalVector--) | Возвращает или задаёт вектор нормали. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Возвращает или задаёт вектор нормали. |
| [getAnchorPoint()](#getAnchorPoint--) | Возвращает или задаёт точку в 3D-пространстве. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | Возвращает или задаёт точку в 3D-пространстве. |
| [getUpVector()](#getUpVector--) | Возвращает или задаёт вектор, представляющий направление вверх. |
| [setUpVector(float[] value)](#setUpVector-float---) | Возвращает или задаёт вектор, представляющий направление вверх. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Версия. Только для чтения long.

**Возвращаемое значение:**
long
### getNormalVector() {#getNormalVector--}
```
public final float[] getNormalVector()
```


Возвращает или задаёт вектор нормали. Точнее, этот атрибут определяет вектор, перпендикулярный плоскости заднего фона. Вектор представляется массивом из 3 значений float, определяющих координаты X, Y и Z. Чтение/запись float[].

**Возвращаемое значение:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public final void setNormalVector(float[] value)
```


Возвращает или задаёт вектор нормали. Точнее, этот атрибут определяет вектор, перпендикулярный плоскости заднего фона. Вектор представляется массивом из 3 значений float, определяющих координаты X, Y и Z. Чтение/запись float[].

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public final float[] getAnchorPoint()
```


Возвращает или задаёт точку в 3D-пространстве. Эта точка является точкой в пространстве, фиксирующей плоскость заднего фона. 3D-точка представляется массивом из 3 значений float, определяющих координаты X, Y и Z. Чтение/запись float[].

**Возвращаемое значение:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public final void setAnchorPoint(float[] value)
```


Возвращает или задаёт точку в 3D-пространстве. Эта точка является точкой в пространстве, фиксирующей плоскость заднего фона. 3D-точка представляется массивом из 3 значений float, определяющих координаты X, Y и Z. Чтение/запись float[].

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public final float[] getUpVector()
```


Возвращает или задаёт вектор, представляющий направление вверх. Точнее, этот атрибут определяет вектор, представляющий направление вверх относительно плоскости заднего фона. Вектор представляется массивом из 3 значений float, определяющих координаты X, Y и Z. Чтение/запись float[].

**Возвращаемое значение:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public final void setUpVector(float[] value)
```


Возвращает или задаёт вектор, представляющий направление вверх. Точнее, этот атрибут определяет вектор, представляющий направление вверх относительно плоскости заднего фона. Вектор представляется массивом из 3 значений float, определяющих координаты X, Y и Z. Чтение/запись float[].

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float[] |  |