---
title: MotionEffect
second_title: Справочник API Aspose.Slides для Java
description: Представляет поведение эффекта движения.
type: docs
url: /ru/com.aspose.slides/motioneffect/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.Behavior](../../com.aspose.slides/behavior)

**Все реализованные интерфейсы:**
[com.aspose.slides.IMotionEffect](../../com.aspose.slides/imotioneffect)
```
public class MotionEffect extends Behavior implements IMotionEffect
```

Представляет поведение эффекта движения.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MotionEffect()](#MotionEffect--) |  |

## Методы

| Метод | Описание |
| --- | --- |
| [getFrom()](#getFrom--) | Указывает координату x/y, от которой начинается анимация (в процентах). |
| [setFrom(Point2D.Float value)](#setFrom-java.awt.geom.Point2D.Float-) | Указывает координату x/y, от которой начинается анимация (в процентах). |
| [getTo()](#getTo--) | Указывает целевое положение для эффекта движения анимации (в процентах). |
| [setTo(Point2D.Float value)](#setTo-java.awt.geom.Point2D.Float-) | Указывает целевое положение для эффекта движения анимации (в процентах). |
| [getBy()](#getBy--) | Описывает относительное смещение для анимации (в процентах). |
| [setBy(Point2D.Float value)](#setBy-java.awt.geom.Point2D.Float-) | Описывает относительное смещение для анимации (в процентах). |
| [getRotationCenter()](#getRotationCenter--) | Описывает центр вращения, используемый для вращения траектории движения на угол X. |
| [setRotationCenter(Point2D.Float value)](#setRotationCenter-java.awt.geom.Point2D.Float-) | Описывает центр вращения, используемый для вращения траектории движения на угол X. |
| [getOrigin()](#getOrigin--) | Указывает, относительно чего находится исходная точка траектории движения, например макет слайда или родительский объект. |
| [setOrigin(int value)](#setOrigin-int-) | Указывает, относительно чего находится исходная точка траектории движения, например макет слайда или родительский объект. |
| [getPath()](#getPath--) | Указывает примитив пути, за которым следуют координаты для движения анимации. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Указывает примитив пути, за которым следуют координаты для движения анимации. |
| [getPathEditMode()](#getPathEditMode--) | Указывает, как траектория движения перемещается при перемещении фигуры. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Указывает, как траектория движения перемещается при перемещении фигуры. |
| [getAngle()](#getAngle--) | Описывает относительный угол траектории движения. |
| [setAngle(float value)](#setAngle-float-) | Описывает относительный угол траектории движения. |

### MotionEffect() {#MotionEffect--}
```
public MotionEffect()
```

### getFrom() {#getFrom--}
```
public final Point2D.Float getFrom()
```

Указывает координату x/y, от которой начинается анимация (в процентах). Чтение/запись java.awt.geom.Point2D.Float.

**Возвращаемое значение:**
java.awt.geom.Point2D.Float

### setFrom(Point2D.Float value) {#setFrom-java.awt.geom.Point2D.Float-}
```
public final void setFrom(Point2D.Float value)
```

Указывает координату x/y, от которой начинается анимация (в процентах). Чтение/запись java.awt.geom.Point2D.Float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getTo() {#getTo--}
```
public final Point2D.Float getTo()
```

Указывает целевое положение для эффекта движения анимации (в процентах). Чтение/запись java.awt.geom.Point2D.Float.

**Возвращаемое значение:**
java.awt.geom.Point2D.Float

### setTo(Point2D.Float value) {#setTo-java.awt.geom.Point2D.Float-}
```
public final void setTo(Point2D.Float value)
```

Указывает целевое положение для эффекта движения анимации (в процентах). Чтение/запись java.awt.geom.Point2D.Float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getBy() {#getBy--}
```
public final Point2D.Float getBy()
```

Описывает относительное смещение для анимации (в процентах). Чтение/запись java.awt.geom.Point2D.Float.

**Возвращаемое значение:**
java.awt.geom.Point2D.Float

### setBy(Point2D.Float value) {#setBy-java.awt.geom.Point2D.Float-}
```
public final void setBy(Point2D.Float value)
```

Описывает относительное смещение для анимации (в процентах). Чтение/запись java.awt.geom.Point2D.Float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getRotationCenter() {#getRotationCenter--}
```
public final Point2D.Float getRotationCenter()
```

Описывает центр вращения, используемый для вращения траектории движения на угол X. Чтение/запись java.awt.geom.Point2D.Float.

**Возвращаемое значение:**
java.awt.geom.Point2D.Float

### setRotationCenter(Point2D.Float value) {#setRotationCenter-java.awt.geom.Point2D.Float-}
```
public final void setRotationCenter(Point2D.Float value)
```

Описывает центр вращения, используемый для вращения траектории движения на угол X. Чтение/запись java.awt.geom.Point2D.Float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getOrigin() {#getOrigin--}
```
public final int getOrigin()
```

Указывает, относительно чего находится исходная точка траектории движения, например макет слайда или родительский объект. Чтение/запись [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Возвращаемое значение:**
int

### setOrigin(int value) {#setOrigin-int-}
```
public final void setOrigin(int value)
```

Указывает, относительно чего находится исходная точка траектории движения, например макет слайда или родительский объект. Чтение/запись [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public final IMotionPath getPath()
```

Указывает примитив пути, за которым следуют координаты для движения анимации. Чтение/запись [IMotionPath](../../com.aspose.slides/imotionpath).

**Возвращаемое значение:**
[IMotionPath](../../com.aspose.slides/imotionpath)

### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public final void setPath(IMotionPath value)
```

Указывает примитив пути, за которым следуют координаты для движения анимации. Чтение/запись [IMotionPath](../../com.aspose.slides/imotionpath).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public final int getPathEditMode()
```

Указывает, как траектория движения перемещается при перемещении фигуры. Чтение/запись [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Возвращаемое значение:**
int

### setPathEditMode(int value) {#setPathEditMode-int-}
```
public final void setPathEditMode(int value)
```

Указывает, как траектория движения перемещается при перемещении фигуры. Чтение/запись [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public final float getAngle()
```

Описывает относительный угол траектории движения. Чтение/запись float.

**Возвращаемое значение:**
float

### setAngle(float value) {#setAngle-float-}
```
public final void setAngle(float value)
```

Описывает относительный угол траектории движения. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |