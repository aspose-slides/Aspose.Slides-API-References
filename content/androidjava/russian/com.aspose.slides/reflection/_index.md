---
title: Reflection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет эффект отражения.
type: docs
url: /ru/com.aspose.slides/reflection/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IReflection](../../com.aspose.slides/ireflection), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class Reflection implements IReflection, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Представляет эффект Reflection.
## Методы

| Метод | Описание |
| --- | --- |
| [getStartPosAlpha()](#getStartPosAlpha--) | Задает начальную позицию (по градиенту альфа) начального значения альфа (в процентах). |
| [setStartPosAlpha(float value)](#setStartPosAlpha-float-) | Задает начальную позицию (по градиенту альфа) начального значения альфа (в процентах). |
| [getEndPosAlpha()](#getEndPosAlpha--) | Задает конечную позицию (по градиенту альфа) конечного значения альфа (в процентах). |
| [setEndPosAlpha(float value)](#setEndPosAlpha-float-) | Задает конечную позицию (по градиенту альфа) конечного значения альфа (в процентах). |
| [getFadeDirection()](#getFadeDirection--) | Задает направление смещения отражения. |
| [setFadeDirection(float value)](#setFadeDirection-float-) | Задает направление смещения отражения. |
| [getStartReflectionOpacity()](#getStartReflectionOpacity--) | Начальная непрозрачность отражения. |
| [setStartReflectionOpacity(float value)](#setStartReflectionOpacity-float-) | Начальная непрозрачность отражения. |
| [getEndReflectionOpacity()](#getEndReflectionOpacity--) | Конечная непрозрачность отражения. |
| [setEndReflectionOpacity(float value)](#setEndReflectionOpacity-float-) | Конечная непрозрачность отражения. |
| [getBlurRadius()](#getBlurRadius--) | Радиус размытия. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Радиус размытия. |
| [getDirection()](#getDirection--) | Направление отражения. |
| [setDirection(float value)](#setDirection-float-) | Направление отражения. |
| [getDistance()](#getDistance--) | Расстояние отражения. |
| [setDistance(double value)](#setDistance-double-) | Расстояние отражения. |
| [getRectangleAlign()](#getRectangleAlign--) | Выравнивание прямоугольника. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | Выравнивание прямоугольника. |
| [getSkewHorizontal()](#getSkewHorizontal--) | Задает угол горизонтального наклона. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | Задает угол горизонтального наклона. |
| [getSkewVertical()](#getSkewVertical--) | Задает угол вертикального наклона. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | Задает угол вертикального наклона. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | Указывает, должно ли отражение вращаться вместе с фигурой при её вращении. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | Указывает, должно ли отражение вращаться вместе с фигурой при её вращении. |
| [getScaleHorizontal()](#getScaleHorizontal--) | Задает горизонтальный коэффициент масштабирования, отрицательное значение приводит к отражению. |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | Задает горизонтальный коэффициент масштабирования, отрицательное значение приводит к отражению. |
| [getScaleVertical()](#getScaleVertical--) | Задает вертикальный коэффициент масштабирования, отрицательное значение приводит к отражению. |
| [setScaleVertical(double value)](#setScaleVertical-double-) | Задает вертикальный коэффициент масштабирования, отрицательное значение приводит к отражению. |
| [getEffective()](#getEffective--) | Получает эффективные данные эффекта Reflection с учётом наследования. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный [Reflection](../../com.aspose.slides/reflection) текущему [Reflection](../../com.aspose.slides/reflection). |
| [hashCode()](#hashCode--) | Служит хеш-функцией для конкретного типа. |

### getStartPosAlpha() {#getStartPosAlpha--}
```
public final float getStartPosAlpha()
```

Задает начальную позицию (по градиенту альфа) начального значения альфа (в процентах). Чтение/запись float.

**Возвращаемое значение:**
float

### setStartPosAlpha(float value) {#setStartPosAlpha-float-}
```
public final void setStartPosAlpha(float value)
```

Задает начальную позицию (по градиенту альфа) начального значения альфа (в процентах). Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getEndPosAlpha() {#getEndPosAlpha--}
```
public final float getEndPosAlpha()
```

Задает конечную позицию (по градиенту альфа) конечного значения альфа (в процентах). Чтение/запись float.

**Возвращаемое значение:**
float

### setEndPosAlpha(float value) {#setEndPosAlpha-float-}
```
public final void setEndPosAlpha(float value)
```

Задает конечную позицию (по градиенту альфа) конечного значения альфа (в процентах). Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getFadeDirection() {#getFadeDirection--}
```
public final float getFadeDirection()
```

Задает направление смещения отражения (угол). Чтение/запись float.

**Возвращаемое значение:**
float

### setFadeDirection(float value) {#setFadeDirection-float-}
```
public final void setFadeDirection(float value)
```

Задает направление смещения отражения (угол). Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getStartReflectionOpacity() {#getStartReflectionOpacity--}
```
public final float getStartReflectionOpacity()
```

Начальная непрозрачность отражения (в процентах). Чтение/запись float.

**Возвращаемое значение:**
float

### setStartReflectionOpacity(float value) {#setStartReflectionOpacity-float-}
```
public final void setStartReflectionOpacity(float value)
```

Начальная непрозрачность отражения (в процентах). Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getEndReflectionOpacity() {#getEndReflectionOpacity--}
```
public final float getEndReflectionOpacity()
```

Конечная непрозрачность отражения (в процентах). Чтение/запись float.

**Возвращаемое значение:**
float

### setEndReflectionOpacity(float value) {#setEndReflectionOpacity-float-}
```
public final void setEndReflectionOpacity(float value)
```

Конечная непрозрачность отражения (в процентах). Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getBlurRadius() {#getBlurRadius--}
```
public final double getBlurRadius()
```

Радиус размытия. Чтение/запись double.

**Возвращаемое значение:**
double

### setBlurRadius(double value) {#setBlurRadius-double-}
```
public final void setBlurRadius(double value)
```

Радиус размытия. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public final float getDirection()
```

Направление отражения. Чтение/запись float.

**Возвращаемое значение:**
float

### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

Направление отражения. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public final double getDistance()
```

Расстояние отражения. Чтение/запись double.

**Возвращаемое значение:**
double

### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

Расстояние отражения. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getRectangleAlign() {#getRectangleAlign--}
```
public final byte getRectangleAlign()
```

Выравнивание прямоугольника. Чтение/запись [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Возвращаемое значение:**
byte

### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public final void setRectangleAlign(byte value)
```

Выравнивание прямоугольника. Чтение/запись [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public final double getSkewHorizontal()
```

Задает угол горизонтального наклона. Чтение/запись double.

**Возвращаемое значение:**
double

### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public final void setSkewHorizontal(double value)
```

Задает угол горизонтального наклона. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public final double getSkewVertical()
```

Задает угол вертикального наклона. Чтение/запись double.

**Возвращаемое значение:**
double

### setSkewVertical(double value) {#setSkewVertical-double-}
```
public final void setSkewVertical(double value)
```

Задает угол вертикального наклона. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public final boolean getRotateShadowWithShape()
```

Указывает, должно ли отражение вращаться вместе с фигурой при её вращении. Чтение/запись boolean.

**Возвращаемое значение:**
boolean

### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public final void setRotateShadowWithShape(boolean value)
```

Указывает, должно ли отражение вращаться вместе с фигурой при её вращении. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public final double getScaleHorizontal()
```

Задает горизонтальный коэффициент масштабирования, отрицательное значение приводит к отражению (в процентах). Чтение/запись double.

**Возвращаемое значение:**
double

### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public final void setScaleHorizontal(double value)
```

Задает горизонтальный коэффициент масштабирования, отрицательное значение приводит к отражению (в процентах). Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public final double getScaleVertical()
```

Задает вертикальный коэффициент масштабирования, отрицательное значение приводит к отражению (в процентах). Чтение/запись double.

**Возвращаемое значение:**
double

### setScaleVertical(double value) {#setScaleVertical-double-}
```
public final void setScaleVertical(double value)
```

Задает вертикальный коэффициент масштабирования, отрицательное значение приводит к отражению (в процентах). Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getEffective() {#getEffective--}
```
public final IReflectionEffectiveData getEffective()
```

Получает эффективные данные эффекта Reflection с учётом наследования.

**Возвращаемое значение:**
[IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata) - [IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata).

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Возвращает объект Parent_Immediate. Только для чтения IDOMObject.

**Возвращаемое значение:**
com.aspose.slides.IDOMObject

### getVersion() {#getVersion--}
```
public final long getVersion()
```

Версия. Только для чтения long.

**Возвращаемое значение:**
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Возвращает родительский IPresentationComponent. Только для чтения [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Возвращаемое значение:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Определяет, равен ли указанный [Reflection](../../com.aspose.slides/reflection) текущему [Reflection](../../com.aspose.slides/reflection).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | [Reflection](../../com.aspose.slides/reflection) для сравнения. |

**Возвращаемое значение:**
boolean - true, если объекты равны; иначе false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Служит хеш-функцией для конкретного типа.

**Возвращаемое значение:**
int - Хеш-код текущего объекта.