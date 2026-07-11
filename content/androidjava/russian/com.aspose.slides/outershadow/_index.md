---
title: OuterShadow
second_title: Aspose.Slides для Android через справочник API Java
description: Представляет эффект внешней тени.
type: docs
url: /ru/com.aspose.slides/outershadow/
---
**Наследование:**  
java.lang.Object

**Все реализованные интерфейсы:**  
[com.aspose.slides.IOuterShadow](../../com.aspose.slides/ioutershadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class OuterShadow implements IOuterShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Представляет эффект внешней тени.
## Методы

| Метод | Описание |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Радиус размытия в пунктах. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Радиус размытия в пунктах. |
| [getDirection()](#getDirection--) | Направление тени в градусах. |
| [setDirection(float value)](#setDirection-float-) | Направление тени в градусах. |
| [getDistance()](#getDistance--) | Расстояние тени от объекта в пунктах. |
| [setDistance(double value)](#setDistance-double-) | Расстояние тени от объекта в пунктах. |
| [getShadowColor()](#getShadowColor--) | Цвет тени. |
| [getRectangleAlign()](#getRectangleAlign--) | Выравнивание прямоугольника. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | Выравнивание прямоугольника. |
| [getSkewHorizontal()](#getSkewHorizontal--) | Угол горизонтального наклона в градусах. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | Угол горизонтального наклона в градусах. |
| [getSkewVertical()](#getSkewVertical--) | Угол вертикального наклона в градусах. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | Угол вертикального наклона в градусах. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | Указывает, вращается ли тень вместе с фигурой. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | Указывает, вращается ли тень вместе с фигурой. |
| [getScaleHorizontal()](#getScaleHorizontal--) | Коэффициент горизонтального масштабирования в процентах от исходного размера. |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | Коэффициент горизонтального масштабирования в процентах от исходного размера. |
| [getScaleVertical()](#getScaleVertical--) | Коэффициент вертикального масштабирования в процентах от исходного размера. |
| [setScaleVertical(double value)](#setScaleVertical-double-) | Коэффициент вертикального масштабирования в процентах от исходного размера. |
| [getEffective()](#getEffective--) | Получает эффективные данные эффекта внешней тени с учётом наследования. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный [OuterShadow](../../com.aspose.slides/outershadow) текущему [OuterShadow](../../com.aspose.slides/outershadow). |
| [hashCode()](#hashCode--) | Служит хеш-функцией для конкретного типа. |

### getBlurRadius() {#getBlurRadius--}
```
public final double getBlurRadius()
```

Радиус размытия в пунктах. Значение по умолчанию - 0 pt. Чтение/запись double.

**Возвращает:**  
double

### setBlurRadius(double value) {#setBlurRadius-double-}
```
public final void setBlurRadius(double value)
```

Радиус размытия в пунктах. Значение по умолчанию - 0 pt. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public final float getDirection()
```

Направление тени в градусах. Значение по умолчанию - 0 � (left-to-right). Чтение/запись float.

**Возвращает:**  
float

### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

Направление тени в градусах. Значение по умолчанию - 0 � (left-to-right). Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public final double getDistance()
```

Расстояние тени от объекта в пунктах. Значение по умолчанию - 0 pt. Чтение/запись double.

**Возвращает:**  
double

### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

Расстояние тени от объекта в пунктах. Значение по умолчанию - 0 pt. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```

Цвет тени. Значение по умолчанию - автоматический чёрный (зависит от темы). Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращает:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getRectangleAlign() {#getRectangleAlign--}
```
public final byte getRectangleAlign()
```

Выравнивание прямоугольника. Значение по умолчанию - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Чтение/запись [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Возвращает:**  
byte

### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public final void setRectangleAlign(byte value)
```

Выравнивание прямоугольника. Значение по умолчанию - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Чтение/запись [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public final double getSkewHorizontal()
```

Угол горизонтального наклона в градусах. Значение по умолчанию - 0 �. Чтение/запись double.

**Возвращает:**  
double

### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public final void setSkewHorizontal(double value)
```

Угол горизонтального наклона в градусах. Значение по умолчанию - 0 �. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public final double getSkewVertical()
```

Угол вертикального наклона в градусах. Значение по умолчанию - 0 �. Чтение/запись double.

**Возвращает:**  
double

### setSkewVertical(double value) {#setSkewVertical-double-}
```
public final void setSkewVertical(double value)
```

Угол вертикального наклона в градусах. Значение по умолчанию - 0 �. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public final boolean getRotateShadowWithShape()
```

Указывает, вращается ли тень вместе с фигурой. Значение по умолчанию - true. Чтение/запись boolean.

**Возвращает:**  
boolean

### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public final void setRotateShadowWithShape(boolean value)
```

Указывает, вращается ли тень вместе с фигурой. Значение по умолчанию - true. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public final double getScaleHorizontal()
```

Коэффициент горизонтального масштабирования в процентах от исходного размера. Отрицательное масштабирование вызывает отражение. Значение по умолчанию - 100 %. Чтение/запись double.

**Возвращает:**  
double

### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public final void setScaleHorizontal(double value)
```

Коэффициент горизонтального масштабирования в процентах от исходного размера. Отрицательное масштабирование вызывает отражение. Значение по умолчанию - 100 %. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public final double getScaleVertical()
```

Коэффициент вертикального масштабирования в процентах от исходного размера. Отрицательное масштабирование вызывает отражение. Значение по умолчанию - 100 %. Чтение/запись double.

**Возвращает:**  
double

### setScaleVertical(double value) {#setScaleVertical-double-}
```
public final void setScaleVertical(double value)
```

Коэффициент вертикального масштабирования в процентах от исходного размера. Отрицательное масштабирование вызывает отражение. Значение по умолчанию - 100 %. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getEffective() {#getEffective--}
```
public final IOuterShadowEffectiveData getEffective()
```

Получает эффективные данные эффекта внешней тени с учётом наследования.

**Возвращает:**  
[IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata) - A [IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata).

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Возвращает объект Parent_Immediate. Только для чтения IDOMObject.

**Возвращает:**  
com.aspose.slides.IDOMObject

### getVersion() {#getVersion--}
```
public final long getVersion()
```

Версия. Только для чтения long.

**Возвращает:**  
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Возвращает родительский IPresentationComponent. Только для чтения [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Возвращает:**  
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Определяет, равен ли указанный [OuterShadow](../../com.aspose.slides/outershadow) текущему [OuterShadow](../../com.aspose.slides/outershadow).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | [OuterShadow](../../com.aspose.slides/outershadow) для сравнения. |

**Возвращает:**  
boolean — true, если объекты равны; иначе false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Служит хеш-функцией для конкретного типа.

**Возвращает:**  
int — хеш-код текущего объекта.