---
title: Backdrop3DScene
second_title: Aspose.Slides для Android через справку Java API
description: Определяет плоскость, в которой эффекты, такие как свечение и тень, применяются относительно фигуры, к которой они применяются.
type: docs
url: /ru/com.aspose.slides/backdrop3dscene/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Все реализованные интерфейсы:**
[com.aspose.slides.IBackdrop3DScene](../../com.aspose.slides/ibackdrop3dscene)
```
public final class Backdrop3DScene extends PVIObject implements IBackdrop3DScene
```

Определяет плоскость, в которой эффекты, такие как свечение и тень, применяются относительно фигуры, к которой они применяются.
## Методы

| Метод | Описание |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNormalVector()](#getNormalVector--) | Возвращает или устанавливает нормальный вектор. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Возвращает или устанавливает нормальный вектор. |
| [getAnchorPoint()](#getAnchorPoint--) | Возвращает или устанавливает точку в 3D-пространстве. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | Возвращает или устанавливает точку в 3D-пространстве. |
| [getUpVector()](#getUpVector--) | Возвращает или устанавливает вектор, представляющий направление вверх. |
| [setUpVector(float[] value)](#setUpVector-float---) | Возвращает или устанавливает вектор, представляющий направление вверх. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Версия. Только для чтения long.

**Возвращает:**
long
### getNormalVector() {#getNormalVector--}
```
public final float[] getNormalVector()
```

Возвращает или устанавливает нормальный вектор. Чтобы быть более точным, этот атрибут определяет вектор, перпендикулярный плоскости заднего фона. Вектор представлен массивом из 3 значений float, определяющих координаты X, Y и Z. Чтение/запись float[].

**Возвращает:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public final void setNormalVector(float[] value)
```

Возвращает или устанавливает нормальный вектор. Чтобы быть более точным, этот атрибут определяет вектор, перпендикулярный плоскости заднего фона. Вектор представлен массивом из 3 значений float, определяющих координаты X, Y и Z. Чтение/запись float[].

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float[] |  |
### getAnchorPoint() {#getAnchorPoint--}
```
public final float[] getAnchorPoint()
```

Возвращает или устанавливает точку в 3D-пространстве. Эта точка является точкой в пространстве, которая фиксирует плоскость заднего фона. 3D-точка представлена массивом из 3 значений float, определяющих координаты X, Y и Z. Чтение/запись float[].

**Возвращает:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public final void setAnchorPoint(float[] value)
```

Возвращает или устанавливает точку в 3D-пространстве. Эта точка является точкой в пространстве, которая фиксирует плоскость заднего фона. 3D-точка представлена массивом из 3 значений float, определяющих координаты X, Y и Z. Чтение/запись float[].

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float[] |  |
### getUpVector() {#getUpVector--}
```
public final float[] getUpVector()
```

Возвращает или устанавливает вектор, представляющий направление вверх. Чтобы быть более точным, этот атрибут определяет вектор, представляющий направление вверх относительно плоскости заднего фона. Вектор представлен массивом из 3 значений float, определяющих координаты X, Y и Z. Чтение/запись float[].

**Возвращает:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public final void setUpVector(float[] value)
```

Возвращает или устанавливает вектор, представляющий направление вверх. Чтобы быть более точным, этот атрибут определяет вектор, представляющий направление вверх относительно плоскости заднего фона. Вектор представлен массивом из 3 значений float, определяющих координаты X, Y и Z. Чтение/запись float[].

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float[] |  |