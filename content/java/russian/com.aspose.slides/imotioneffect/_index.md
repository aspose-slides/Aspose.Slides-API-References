---
title: IMotionEffect
second_title: Справочник API Aspose.Slides для Java
description: Представляет поведение эффекта движения.
type: docs
url: /ru/com.aspose.slides/imotioneffect/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IMotionEffect extends IBehavior
```

Представляет поведение эффекта движения.

## Методы

| Метод | Описание |
| --- | --- |
| [getFrom()](#getFrom--) | Указывает координату x/y, с которой начинается анимация (в процентах). |
| [setFrom(Point2D.Float value)](#setFrom-java.awt.geom.Point2D.Float-) | Указывает координату x/y, с которой начинается анимация (в процентах). |
| [getTo()](#getTo--) | Указывает целевое положение для анимационного эффекта движения (в процентах). |
| [setTo(Point2D.Float value)](#setTo-java.awt.geom.Point2D.Float-) | Указывает целевое положение для анимационного эффекта движения (в процентах). |
| [getBy()](#getBy--) | Описывает относительное смещение для анимации (в процентах). |
| [setBy(Point2D.Float value)](#setBy-java.awt.geom.Point2D.Float-) | Описывает относительное смещение для анимации (в процентах). |
| [getRotationCenter()](#getRotationCenter--) | Описывает центр вращения, используемый для вращения траектории движения на угол X. |
| [setRotationCenter(Point2D.Float value)](#setRotationCenter-java.awt.geom.Point2D.Float-) | Описывает центр вращения, используемый для вращения траектории движения на угол X. |
| [getOrigin()](#getOrigin--) | Указывает, относительно чего находится начало траектории движения, например относительно макета слайда или родителя. |
| [setOrigin(int value)](#setOrigin-int-) | Указывает, относительно чего находится начало траектории движения, например относительно макета слайда или родителя. |
| [getPath()](#getPath--) | Указывает примитив пути, сопровождаемый координатами для анимационного движения. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Указывает примитив пути, сопровождаемый координатами для анимационного движения. |
| [getPathEditMode()](#getPathEditMode--) | Указывает, как траектория движения перемещается при перемещении фигуры. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Указывает, как траектория движения перемещается при перемещении фигуры. |
| [getAngle()](#getAngle--) | Описывает относительный угол траектории движения. |
| [setAngle(float value)](#setAngle-float-) | Описывает относительный угол траектории движения. |

### getFrom() {#getFrom--}
```
public abstract Point2D.Float getFrom()
```

Указывает координату x/y, с которой начинается анимация (в процентах). Чтение/запись java.awt.geom.Point2D.Float.

**Возвращаемое значение:**
java.awt.geom.Point2D.Float

### setFrom(Point2D.Float value) {#setFrom-java.awt.geom.Point2D.Float-}
```
public abstract void setFrom(Point2D.Float value)
```

Указывает координату x/y, с которой начинается анимация (в процентах). Чтение/запись java.awt.geom.Point2D.Float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getTo() {#getTo--}
```
public abstract Point2D.Float getTo()
```

Указывает целевое положение для анимационного эффекта движения (в процентах). Чтение/запись java.awt.geom.Point2D.Float.

**Возвращаемое значение:**
java.awt.geom.Point2D.Float

### setTo(Point2D.Float value) {#setTo-java.awt.geom.Point2D.Float-}
```
public abstract void setTo(Point2D.Float value)
```

Указывает целевое положение для анимационного эффекта движения (в процентах). Чтение/запись java.awt.geom.Point2D.Float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getBy() {#getBy--}
```
public abstract Point2D.Float getBy()
```

Описывает относительное смещение для анимации (в процентах). Чтение/запись java.awt.geom.Point2D.Float.

**Возвращаемое значение:**
java.awt.geom.Point2D.Float

### setBy(Point2D.Float value) {#setBy-java.awt.geom.Point2D.Float-}
```
public abstract void setBy(Point2D.Float value)
```

Описывает относительное смещение для анимации (в процентах). Чтение/запись java.awt.geom.Point2D.Float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getRotationCenter() {#getRotationCenter--}
```
public abstract Point2D.Float getRotationCenter()
```

Описывает центр вращения, используемый для вращения траектории движения на угол X. Чтение/запись java.awt.geom.Point2D.Float.

**Возвращаемое значение:**
java.awt.geom.Point2D.Float

### setRotationCenter(Point2D.Float value) {#setRotationCenter-java.awt.geom.Point2D.Float-}
```
public abstract void setRotationCenter(Point2D.Float value)
```

Описывает центр вращения, используемый для вращения траектории движения на угол X. Чтение/запись java.awt.geom.Point2D.Float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```

Указывает, относительно чего находится начало траектории движения, например относительно макета слайда или родителя. Чтение/запись [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Возвращаемое значение:**
int

### setOrigin(int value) {#setOrigin-int-}
```
public abstract void setOrigin(int value)
```

Указывает, относительно чего находится начало траектории движения, например относительно макета слайда или родителя. Чтение/запись [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public abstract IMotionPath getPath()
```

Указывает примитив пути, сопровождаемый координатами для анимационного движения. Чтение/запись [IMotionPath](../../com.aspose.slides/imotionpath).

**Возвращаемое значение:**
[IMotionPath](../../com.aspose.slides/imotionpath)

### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public abstract void setPath(IMotionPath value)
```

Указывает примитив пути, сопровождаемый координатами для анимационного движения. Чтение/запись [IMotionPath](../../com.aspose.slides/imotionpath).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public abstract int getPathEditMode()
```

Указывает, как траектория движения перемещается при перемещении фигуры. Чтение/запись [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Возвращаемое значение:**
int

### setPathEditMode(int value) {#setPathEditMode-int-}
```
public abstract void setPathEditMode(int value)
```

Указывает, как траектория движения перемещается при перемещении фигуры. Чтение/запись [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public abstract float getAngle()
```

Описывает относительный угол траектории движения. Чтение/запись float.

**Возвращаемое значение:**
float

### setAngle(float value) {#setAngle-float-}
```
public abstract void setAngle(float value)
```

Описывает относительный угол траектории движения. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |