---
title: OuterShadow
second_title: Aspose.Slides для Java — справочник API
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
| [getBlurRadius()](#getBlurRadius--) | Радиус размытия, в пунктах. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Радиус размытия, в пунктах. |
| [getDirection()](#getDirection--) | Направление тени, в градусах. |
| [setDirection(float value)](#setDirection-float-) | Направление тени, в градусах. |
| [getDistance()](#getDistance--) | Расстояние тени от объекта, в пунктах. |
| [setDistance(double value)](#setDistance-double-) | Расстояние тени от объекта, в пунктах. |
| [getShadowColor()](#getShadowColor--) | Цвет тени. |
| [getRectangleAlign()](#getRectangleAlign--) | Выравнивание прямоугольника. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | Выравнивание прямоугольника. |
| [getSkewHorizontal()](#getSkewHorizontal--) | Горизонтальный угол наклона, в градусах. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | Горизонтальный угол наклона, в градусах. |
| [getSkewVertical()](#getSkewVertical--) | Вертикальный угол наклона, в градусах. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | Вертикальный угол наклона, в градусах. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | Указывает, вращается ли тень вместе с фигурой. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | Указывает, вращается ли тень вместе с фигурой. |
| [getScaleHorizontal()](#getScaleHorizontal--) | Горизонтальный коэффициент масштабирования, в процентах от исходного размера. |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | Горизонтальный коэффициент масштабирования, в процентах от исходного размера. |
| [getScaleVertical()](#getScaleVertical--) | Вертикальный коэффициент масштабирования, в процентах от исходного размера. |
| [setScaleVertical(double value)](#setScaleVertical-double-) | Вертикальный коэффициент масштабирования, в процентах от исходного размера. |
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

Радиус размытия, в пунктах. Значение по умолчанию — 0 pt. Чтение/запись double.

**Возвращаемое значение:**  
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public final void setBlurRadius(double value)
```

Радиус размытия, в пунктах. Значение по умолчанию — 0 pt. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |
### getDirection() {#getDirection--}
```
public final float getDirection()
```

Направление тени, в градусах. Значение по умолчанию — 0 � (слева направо). Чтение/запись float.

**Возвращаемое значение:**  
float
### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

Направление тени, в градусах. Значение по умолчанию — 0 � (слева направо). Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public final double getDistance()
```

Расстояние тени от объекта, в пунктах. Значение по умолчанию — 0 pt. Чтение/запись double.

**Возвращаемое значение:**  
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

Расстояние тени от объекта, в пунктах. Значение по умолчанию — 0 pt. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```

Цвет тени. Значение по умолчанию — автоматический чёрный (зависит от темы). Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращаемое значение:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getRectangleAlign() {#getRectangleAlign--}
```
public final byte getRectangleAlign()
```

Выравнивание прямоугольника. Значение по умолчанию — [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Чтение/запись [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Возвращаемое значение:**  
byte
### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public final void setRectangleAlign(byte value)
```

Выравнивание прямоугольника. Значение по умолчанию — [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Чтение/запись [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getSkewHorizontal() {#getSkewHorizontal--}
```
public final double getSkewHorizontal()
```

Горизонтальный угол наклона, в градусах. Значение по умолчанию — 0 �. Чтение/запись double.

**Возвращаемое значение:**  
double
### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public final void setSkewHorizontal(double value)
```

Горизонтальный угол наклона, в градусах. Значение по умолчанию — 0 �. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |
### getSkewVertical() {#getSkewVertical--}
```
public final double getSkewVertical()
```

Вертикальный угол наклона, в градусах. Значение по умолчанию — 0 �. Чтение/запись double.

**Возвращаемое значение:**  
double
### setSkewVertical(double value) {#setSkewVertical-double-}
```
public final void setSkewVertical(double value)
```

Вертикальный угол наклона, в градусах. Значение по умолчанию — 0 �. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |
### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public final boolean getRotateShadowWithShape()
```

Указывает, вращается ли тень вместе с фигурой. Значение по умолчанию — true. Чтение/запись boolean.

**Возвращаемое значение:**  
boolean
### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public final void setRotateShadowWithShape(boolean value)
```

Указывает, вращается ли тень вместе с фигурой. Значение по умолчанию — true. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getScaleHorizontal() {#getScaleHorizontal--}
```
public final double getScaleHorizontal()
```

Горизонтальный коэффициент масштабирования, в процентах от исходного размера. Отрицательное значение приводит к отражению. Значение по умолчанию — 100 %. Чтение/запись double.

**Возвращаемое значение:**  
double
### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public final void setScaleHorizontal(double value)
```

Горизонтальный коэффициент масштабирования, в процентах от исходного размера. Отрицательное значение приводит к отражению. Значение по умолчанию — 100 %. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |
### getScaleVertical() {#getScaleVertical--}
```
public final double getScaleVertical()
```

Вертикальный коэффициент масштабирования, в процентах от исходного размера. Отрицательное значение приводит к отражению. Значение по умолчанию — 100 %. Чтение/запись double.

**Возвращаемое значение:**  
double
### setScaleVertical(double value) {#setScaleVertical-double-}
```
public final void setScaleVertical(double value)
```

Вертикальный коэффициент масштабирования, в процентах от исходного размера. Отрицательное значение приводит к отражению. Значение по умолчанию — 100 %. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |
### getEffective() {#getEffective--}
```
public final IOuterShadowEffectiveData getEffective()
```

Получает эффективные данные эффекта внешней тени с учётом наследования.

**Возвращаемое значение:**  
[IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata) — Объект [IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata).
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

Определяет, равен ли указанный [OuterShadow](../../com.aspose.slides/outershadow) текущему [OuterShadow](../../com.aspose.slides/outershadow).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | [OuterShadow](../../com.aspose.slides/outershadow) для сравнения. |

**Возвращаемое значение:**  
boolean — true, если объекты равны; иначе false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Служит хеш-функцией для конкретного типа.

**Возвращаемое значение:**  
int — Хеш-код текущего объекта.