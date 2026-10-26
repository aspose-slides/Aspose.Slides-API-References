---
title: InnerShadow
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет эффект внутренней тени.
type: docs
url: /ru/com.aspose.slides/innershadow/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IInnerShadow](../../com.aspose.slides/iinnershadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class InnerShadow implements IInnerShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Представляет эффект внутренней тени.
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
| [getEffective()](#getEffective--) | Получает эффективные данные эффекта внутренней тени с применённым наследованием. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный [InnerShadow](../../com.aspose.slides/innershadow) текущему [InnerShadow](../../com.aspose.slides/innershadow). |
| [hashCode()](#hashCode--) | Служит хеш-функцией для конкретного типа. |
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

Направление тени. Чтение/запись float.

**Возвращаемое значение:**
float
### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

Направление тени. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public final double getDistance()
```

Расстояние тени. Чтение/запись double.

**Возвращаемое значение:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

Расстояние тени. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```

Цвет тени. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращаемое значение:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IInnerShadowEffectiveData getEffective()
```

Получает эффективные данные эффекта внутренней тени с применённым наследованием.

**Возвращаемое значение:**
[IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata) — [IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata).
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

Определяет, равен ли указанный [InnerShadow](../../com.aspose.slides/innershadow) текущему [InnerShadow](../../com.aspose.slides/innershadow).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | [InnerShadow](../../com.aspose.slides/innershadow) для сравнения. |

**Возвращаемое значение:**
boolean — true, если объекты равны; иначе false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Служит хеш-функцией для конкретного типа.

**Возвращаемое значение:**
int — хеш-код текущего объекта.