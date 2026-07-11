---
title: MotionEffect
second_title: Aspose.Slides для Android через справочник Java API
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
| [getFrom()](#getFrom--) | Указывает координату x/y, с которой начинается анимация (в процентах). |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | Указывает координату x/y, с которой начинается анимация (в процентах). |
| [getTo()](#getTo--) | Указывает целевое положение для эффекта движения анимации (в процентах). |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | Указывает целевое положение для эффекта движения анимации (в процентах). |
| [getBy()](#getBy--) | Описывает относительное значение смещения для анимации (в процентах). |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | Описывает относительное значение смещения для анимации (в процентах). |
| [getRotationCenter()](#getRotationCenter--) | Описывает центр вращения, используемый для вращения траектории движения на угол X. |
| [setRotationCenter(PointF value)](#setRotationCenter-android.graphics.PointF-) | Описывает центр вращения, используемый для вращения траектории движения на угол X. |
| [getOrigin()](#getOrigin--) | Указывает, относительно чего определяется начало траектории движения, например относительно макета слайда или родительского объекта. |
| [setOrigin(int value)](#setOrigin-int-) | Указывает, относительно чего определяется начало траектории движения, например относительно макета слайда или родительского объекта. |
| [getPath()](#getPath--) | Указывает примитив пути, за которым следуют координаты для анимации движения. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Указывает примитив пути, за которым следуют координаты для анимации движения. |
| [getPathEditMode()](#getPathEditMode--) | Указывает, как траектория движения перемещается при перемещении формы. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Указывает, как траектория движения перемещается при перемещении формы. |
| [getAngle()](#getAngle--) | Описывает относительный угол траектории движения. |
| [setAngle(float value)](#setAngle-float-) | Описывает относительный угол траектории движения. |
### MotionEffect() {#MotionEffect--}
```
public MotionEffect()
```


### getFrom() {#getFrom--}
```
public final PointF getFrom()
```


Указывает координату x/y, с которой начинается анимация (в процентах). Чтение/запись android.graphics.PointF.

**Возвращаемое значение:**
android.graphics.PointF
### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public final void setFrom(PointF value)
```


Указывает координату x/y, с которой начинается анимация (в процентах). Чтение/запись android.graphics.PointF.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getTo() {#getTo--}
```
public final PointF getTo()
```


Указывает целевое положение для эффекта движения анимации (в процентах). Чтение/запись android.graphics.PointF.

**Возвращаемое значение:**
android.graphics.PointF
### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public final void setTo(PointF value)
```


Указывает целевое положение для эффекта движения анимации (в процентах). Чтение/запись android.graphics.PointF.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getBy() {#getBy--}
```
public final PointF getBy()
```


Описывает относительное значение смещения для анимации (в процентах). Чтение/запись android.graphics.PointF.

**Возвращаемое значение:**
android.graphics.PointF
### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public final void setBy(PointF value)
```


Описывает относительное значение смещения для анимации (в процентах). Чтение/запись android.graphics.PointF.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getRotationCenter() {#getRotationCenter--}
```
public final PointF getRotationCenter()
```


Описывает центр вращения, используемый для вращения траектории движения на угол X. Чтение/запись android.graphics.PointF.

**Возвращаемое значение:**
android.graphics.PointF
### setRotationCenter(PointF value) {#setRotationCenter-android.graphics.PointF-}
```
public final void setRotationCenter(PointF value)
```


Описывает центр вращения, используемый для вращения траектории движения на угол X. Чтение/запись android.graphics.PointF.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getOrigin() {#getOrigin--}
```
public final int getOrigin()
```


Указывает, относительно чего определяется начало траектории движения, например относительно макета слайда или родительского объекта. Чтение/запись [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Возвращаемое значение:**
int
### setOrigin(int value) {#setOrigin-int-}
```
public final void setOrigin(int value)
```


Указывает, относительно чего определяется начало траектории движения, например относительно макета слайда или родительского объекта. Чтение/запись [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public final IMotionPath getPath()
```


Указывает примитив пути, за которым следуют координаты для анимации движения. Чтение/запись [IMotionPath](../../com.aspose.slides/imotionpath).

**Возвращаемое значение:**
[IMotionPath](../../com.aspose.slides/imotionpath)
### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public final void setPath(IMotionPath value)
```


Указывает примитив пути, за которым следуют координаты для анимации движения. Чтение/запись [IMotionPath](../../com.aspose.slides/imotionpath).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public final int getPathEditMode()
```


Указывает, как траектория движения перемещается при перемещении формы. Чтение/запись [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Возвращаемое значение:**
int
### setPathEditMode(int value) {#setPathEditMode-int-}
```
public final void setPathEditMode(int value)
```


Указывает, как траектория движения перемещается при перемещении формы. Чтение/запись [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

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