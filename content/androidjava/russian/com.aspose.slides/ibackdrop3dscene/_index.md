---
title: IBackdrop3DScene
second_title: Aspose.Slides for Android via Java API Reference
description: Defines a plane in which effects such as glow and shadow are applied in relation to the shape they are being applied to.
type: docs
url: /ru/com.aspose.slides/ibackdrop3dscene/
---```
public interface IBackdrop3DScene
```

Определяет плоскость, в которой эффекты, такие как свечение и тень, применяются относительно формы, к которой они применяются.
## Методы

| Метод | Описание |
| --- | --- |
| [getNormalVector()](#getNormalVector--) | Возвращает или задает нормальный вектор. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Возвращает или задает нормальный вектор. |
| [getAnchorPoint()](#getAnchorPoint--) | Возвращает или задает точку в 3D-пространстве. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | Возвращает или задает точку в 3D-пространстве. |
| [getUpVector()](#getUpVector--) | Возвращает или задает вектор, указывающий вверх. |
| [setUpVector(float[] value)](#setUpVector-float---) | Возвращает или задает вектор, указывающий вверх. |
### getNormalVector() {#getNormalVector--}
```
public abstract float[] getNormalVector()
```


Возвращает или задает нормальный вектор. Точнее, этот атрибут определяет вектор, нормальный к поверхности плоскости фона. Вектор представлен массивом из 3 значений float, определяющих координаты X, Y и Z. Чтение/запись float[].

**Возвращаемое значение:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public abstract void setNormalVector(float[] value)
```


Возвращает или задает нормальный вектор. Точнее, этот атрибут определяет вектор, нормальный к поверхности плоскости фона. Вектор представлен массивом из 3 значений float, определяющих координаты X, Y и Z. Чтение/запись float[].

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public abstract float[] getAnchorPoint()
```


Возвращает или задает точку в 3D-пространстве. Эта точка фиксирует плоскость фона в пространстве. 3D-точка представлена массивом из 3 значений float, определяющих координаты X, Y и Z. Чтение/запись float[].

**Возвращаемое значение:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public abstract void setAnchorPoint(float[] value)
```


Возвращает или задает точку в 3D-пространстве. Эта точка фиксирует плоскость фона в пространстве. 3D-точка представлена массивом из 3 значений float, определяющих координаты X, Y и Z. Чтение/запись float[].

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public abstract float[] getUpVector()
```


Возвращает или задает вектор, указывающий вверх. Точнее, этот атрибут определяет вектор, указывающий вверх относительно поверхности плоскости фона. Вектор представлен массивом из 3 значений float, определяющих координаты X, Y и Z. Чтение/запись float[].

**Возвращаемое значение:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public abstract void setUpVector(float[] value)
```


Возвращает или задает вектор, указывающий вверх. Точнее, этот атрибут определяет вектор, указывающий вверх относительно поверхности плоскости фона. Вектор представлен массивом из 3 значений float, определяющих координаты X, Y и Z. Чтение/запись float[].

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float[] |  |