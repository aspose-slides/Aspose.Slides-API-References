---
title: IBackdrop3DScene
second_title: Aspose.Slides for Java API Reference
description: Определяет плоскость, в которой эффекты, такие как свечения и тени, применяются относительно фигуры, к которой они применяются.
type: docs
url: /ru/com.aspose.slides/ibackdrop3dscene/
---```
public interface IBackdrop3DScene
```

Определяет плоскость, в которой эффекты, такие как свечения и тени, применяются относительно фигуры, к которой они применяются.
## Методы

| Метод | Описание |
| --- | --- |
| [getNormalVector()](#getNormalVector--) | Возвращает или задает нормальный вектор. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Возвращает или задает нормальный вектор. |
| [getAnchorPoint()](#getAnchorPoint--) | Возвращает или задает точку в 3D пространстве. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | Возвращает или задает точку в 3D пространстве. |
| [getUpVector()](#getUpVector--) | Возвращает или задает вектор, указывающий вверх. |
| [setUpVector(float[] value)](#setUpVector-float---) | Возвращает или задает вектор, указывающий вверх. |
### getNormalVector() {#getNormalVector--}
```
public abstract float[] getNormalVector()
```

Возвращает или задает нормальный вектор. Для более точного определения этот атрибут задаёт вектор, перпендикулярный плоскости фона. Вектор представляется массивом из 3 значений float, определяющих координаты X, Y и Z. Read/write float[].

**Возвращаемое значение:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public abstract void setNormalVector(float[] value)
```

Возвращает или задает нормальный вектор. Для более точного определения этот атрибут задаёт вектор, перпендикулярный плоскости фона. Вектор представляется массивом из 3 значений float, определяющих координаты X, Y и Z. Read/write float[].

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float[] |  |
### getAnchorPoint() {#getAnchorPoint--}
```
public abstract float[] getAnchorPoint()
```

Возвращает или задает точку в 3D пространстве. Эта точка — точка в пространстве, которая фиксирует плоскость фона. Точка представляется массивом из 3 значений float, определяющих координаты X, Y и Z. Read/write float[].

**Возвращаемое значение:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public abstract void setAnchorPoint(float[] value)
```

Возвращает или задает точку в 3D пространстве. Эта точка — точка в пространстве, которая фиксирует плоскость фона. Точка представляется массивом из 3 значений float, определяющих координаты X, Y и Z. Read/write float[].

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float[] |  |
### getUpVector() {#getUpVector--}
```
public abstract float[] getUpVector()
```

Возвращает или задает вектор, указывающий вверх. Для более точного определения этот атрибут задаёт вектор, указывающий вверх относительно плоскости фона. Вектор представляется массивом из 3 значений float, определяющих координаты X, Y и Z. Read/write float[].

**Возвращаемое значение:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public abstract void setUpVector(float[] value)
```

Возвращает или задает вектор, указывающий вверх. Для более точного определения этот атрибут задаёт вектор, указывающий вверх относительно плоскости фона. Вектор представляется массивом из 3 значений float, определяющих координаты X, Y и Z. Read/write float[].

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float[] |  |