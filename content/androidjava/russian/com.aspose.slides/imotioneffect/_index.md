---
title: IMotionEffect
second_title: Aspose.Slides для Android через справочник API Java
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
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | Указывает координату x/y, с которой начинается анимация (в процентах). |
| [getTo()](#getTo--) | Указывает целевое расположение для эффекта движения анимации (в процентах). |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | Указывает целевое расположение для эффекта движения анимации (в процентах). |
| [getBy()](#getBy--) | Описывает относительное значение смещения для анимации (в процентах). |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | Описывает относительное значение смещения для анимации (в процентах). |
| [getRotationCenter()](#getRotationCenter--) | Описывает центр вращения, используемый для вращения траектории движения на угол X. |
| [setRotationCenter(PointF value)](#setRotationCenter-android.graphics.PointF-) | Описывает центр вращения, используемый для вращения траектории движения на угол X. |
| [getOrigin()](#getOrigin--) | Указывает, относительно чего находится исходная точка траектории движения, например макет слайда или родитель. |
| [setOrigin(int value)](#setOrigin-int-) | Указывает, относительно чего находится исходная точка траектории движения, например макет слайда или родитель. |
| [getPath()](#getPath--) | Указывает примитив пути, за которым следуют координаты для движения анимации. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Указывает примитив пути, за которым следуют координаты для движения анимации. |
| [getPathEditMode()](#getPathEditMode--) | Указывает, как траектория движения перемещается при перемещении фигуры. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Указывает, как траектория движения перемещается при перемещении фигуры. |
| [getAngle()](#getAngle--) | Описывает относительный угол траектории движения. |
| [setAngle(float value)](#setAngle-float-) | Описывает относительный угол траектории движения. |

### getFrom() {#getFrom--}
```
public abstract PointF getFrom()
```

Указывает координату x/y, с которой начинается анимация (в процентах). Чтение/запись android.graphics.PointF.

**Возвращаемое значение:**
android.graphics.PointF

### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public abstract void setFrom(PointF value)
```

Указывает координату x/y, с которой начинается анимация (в процентах). Чтение/запись android.graphics.PointF.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getTo() {#getTo--}
```
public abstract PointF getTo()
```

Указывает целевое расположение для эффекта движения анимации (в процентах). Чтение/запись android.graphics.PointF.

**Возвращаемое значение:**
android.graphics.PointF

### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public abstract void setTo(PointF value)
```

Указывает целевое расположение для эффекта движения анимации (в процентах). Чтение/запись android.graphics.PointF.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getBy() {#getBy--}
```
public abstract PointF getBy()
```

Описывает относительное значение смещения для анимации (в процентах). Чтение/запись android.graphics.PointF.

**Возвращаемое значение:**
android.graphics.PointF

### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public abstract void setBy(PointF value)
```

Описывает относительное значение смещения для анимации (в процентах). Чтение/запись android.graphics.PointF.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getRotationCenter() {#getRotationCenter--}
```
public abstract PointF getRotationCenter()
```

Описывает центр вращения, используемый для вращения траектории движения на угол X. Чтение/запись android.graphics.PointF.

**Возвращаемое значение:**
android.graphics.PointF

### setRotationCenter(PointF value) {#setRotationCenter-android.graphics.PointF-}
```
public abstract void setRotationCenter(PointF value)
```

Описывает центр вращения, используемый для вращения траектории движения на угол X. Чтение/запись android.graphics.PointF.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```

Указывает, относительно чего находится исходная точка траектории движения, например макет слайда или родитель. Чтение/запись [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Возвращаемое значение:**
int

### setOrigin(int value) {#setOrigin-int-}
```
public abstract void setOrigin(int value)
```

Указывает, относительно чего находится исходная точка траектории движения, например макет слайда или родитель. Чтение/запись [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public abstract IMotionPath getPath()
```

Указывает примитив пути, за которым следуют координаты для движения анимации. Чтение/запись [IMotionPath](../../com.aspose.slides/imotionpath).

**Возвращаемое значение:**
[IMotionPath](../../com.aspose.slides/imotionpath)

### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public abstract void setPath(IMotionPath value)
```

Указывает примитив пути, за которым следуют координаты для движения анимации. Чтение/запись [IMotionPath](../../com.aspose.slides/imotionpath).

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