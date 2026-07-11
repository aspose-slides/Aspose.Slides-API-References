---
title: IOuterShadow
second_title: Aspose.Slides для Android через Java API Reference
description: Представляет эффект внешней тени.
type: docs
url: /ru/com.aspose.slides/ioutershadow/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IOuterShadow extends IImageTransformOperation, IAccessiblePVIObject<IOuterShadowEffectiveData>
```

Представляет эффект внешней тени.
## Методы

| Метод | Описание |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Радиус размытия, в пунктах. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Радиус размытия, в пунктах. |
| [getDirection()](#getDirection--) | Направление тени, в градусах. |
| [setDirection(float value)](#setDirection-float-) | Направление тени, в градусах. |
| [getDistance()](#getDistance--) | Расстояние тени от объекта, в пунктах. |
| [setDistance(double value)](#setDistance-double-) | Расстояние тени от объекта, в пунктах. |
| [getShadowColor()](#getShadowColor--) | Цвет тени. |
| [getRectangleAlign()](#getRectangleAlign--) | Выравнивание прямоугольника. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | Выравнивание прямоугольника. |
| [getSkewHorizontal()](#getSkewHorizontal--) | Угол горизонтального наклона, в градусах. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | Угол горизонтального наклона, в градусах. |
| [getSkewVertical()](#getSkewVertical--) | Угол вертикального наклона, в градусах. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | Угол вертикального наклона, в градусах. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | Указывает, вращается ли тень вместе с фигурой. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | Указывает, вращается ли тень вместе с фигурой. |
| [getScaleHorizontal()](#getScaleHorizontal--) | Коэффициент горизонтального масштабирования, в процентах от исходного размера. |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | Коэффициент горизонтального масштабирования, в процентах от исходного размера. |
| [getScaleVertical()](#getScaleVertical--) | Коэффициент вертикального масштабирования, в процентах от исходного размера. |
| [setScaleVertical(double value)](#setScaleVertical-double-) | Коэффициент вертикального масштабирования, в процентах от исходного размера. |
### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

Радиус размытия, в пунктах. Значение по умолчанию — 0 pt. Чтение/запись double.

**Возвращаемое значение:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```

Радиус размытия, в пунктах. Значение по умолчанию — 0 pt. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

Направление тени, в градусах. Значение по умолчанию — 0 � (left-to-right). Чтение/запись float.

**Возвращаемое значение:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

Направление тени, в градусах. Значение по умолчанию — 0 � (left-to-right). Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

Расстояние тени от объекта, в пунктах. Значение по умолчанию — 0 pt. Чтение/запись double.

**Возвращаемое значение:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

Расстояние тени от объекта, в пунктах. Значение по умолчанию — 0 pt. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

Цвет тени. Значение по умолчанию — автоматический черный (зависит от темы). Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращаемое значение:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

Выравнивание прямоугольника. Значение по умолчанию — [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Чтение/запись [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Возвращаемое значение:**
byte
### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public abstract void setRectangleAlign(byte value)
```

Выравнивание прямоугольника. Значение по умолчанию — [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Чтение/запись [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

Угол горизонтального наклона, в градусах. Значение по умолчанию — 0 �. Чтение/запись double.

**Возвращаемое значение:**
double
### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public abstract void setSkewHorizontal(double value)
```

Угол горизонтального наклона, в градусах. Значение по умолчанию — 0 �. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

Угол вертикального наклона, в градусах. Значение по умолчанию — 0 �. Чтение/запись double.

**Возвращаемое значение:**
double
### setSkewVertical(double value) {#setSkewVertical-double-}
```
public abstract void setSkewVertical(double value)
```

Угол вертикального наклона, в градусах. Значение по умолчанию — 0 �. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

Указывает, вращается ли тень вместе с фигурой. Значение по умолчанию — true. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public abstract void setRotateShadowWithShape(boolean value)
```

Указывает, вращается ли тень вместе с фигурой. Значение по умолчанию — true. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

Коэффициент горизонтального масштабирования, в процентах от исходного размера. Отрицательное масштабирование приводит к отражению. Значение по умолчанию — 100 %. Чтение/запись double.

**Возвращаемое значение:**
double
### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public abstract void setScaleHorizontal(double value)
```

Коэффициент горизонтального масштабирования, в процентах от исходного размера. Отрицательное масштабирование приводит к отражению. Значение по умолчанию — 100 %. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

Коэффициент вертикального масштабирования, в процентах от исходного размера. Отрицательное масштабирование приводит к отражению. Значение по умолчанию — 100 %. Чтение/запись double.

**Возвращаемое значение:**
double
### setScaleVertical(double value) {#setScaleVertical-double-}
```
public abstract void setScaleVertical(double value)
```

Коэффициент вертикального масштабирования, в процентах от исходного размера. Отрицательное масштабирование приводит к отражению. Значение по умолчанию — 100 %. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |