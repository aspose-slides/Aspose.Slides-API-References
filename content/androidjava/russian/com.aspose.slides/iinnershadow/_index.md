---
title: IInnerShadow
second_title: Aspose.Slides для Android через Java API
description: Представляет внутренний эффект тени.
type: docs
url: /ru/com.aspose.slides/iinnershadow/
---
**Все реализованные интерфейсы:**  
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject  
```
public interface IInnerShadow extends IImageTransformOperation, IAccessiblePVIObject<IInnerShadowEffectiveData>
```

Представляет внутренний эффект тени.
## Методы

| Метод | Описание |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Радиус размытия. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Радиус размытия. |
| [getDirection()](#getDirection--) | Направление тени. |
| [setDirection(float value)](#setDirection-float-) | Направление тени. |
| [getDistance()](#getDistance--) | Расстояние тени. |
| [setDistance(double value)](#setDistance-double-) | Расстояние тени. |
| [getShadowColor()](#getShadowColor--) | Цвет тени. |

### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

Радиус размытия. Чтение/запись double.

**Возвращаемое значение:**  
double

### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```

Радиус размытия. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

Направление тени. Чтение/запись float.

**Возвращаемое значение:**  
float

### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

Направление тени. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

Расстояние тени. Чтение/запись double.

**Возвращаемое значение:**  
double

### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

Расстояние тени. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

Цвет тени. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращаемое значение:**  
[IColorFormat](../../com.aspose.slides/icolorformat)