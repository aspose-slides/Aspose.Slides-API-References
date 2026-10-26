---
title: Glow
second_title: Aspose.Slides для Android через Java API
description: Представляет эффект Glow, при котором цветная размытая окантовка добавляется за пределами краёв объекта.
type: docs
url: /ru/com.aspose.slides/glow/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IGlow](../../com.aspose.slides/iglow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class Glow implements IGlow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Представляет эффект Glow, в котором цветная размытая окантовка добавляется за пределами краёв объекта.
## Методы

| Метод | Описание |
| --- | --- |
| [getRadius()](#getRadius--) | Радиус. |
| [setRadius(double value)](#setRadius-double-) | Радиус. |
| [getColor()](#getColor--) | Формат цвета. |
| [getEffective()](#getEffective--) | Получает данные эффекта Glow с применённым наследованием. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный [Glow](../../com.aspose.slides/glow) текущему [Glow](../../com.aspose.slides/glow). |
| [hashCode()](#hashCode--) | Служит хэш-функцией для определённого типа. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```

Радиус. Чтение/запись double.

**Возвращаемое значение:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

Радиус. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

Формат цвета. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращаемое значение:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IGlowEffectiveData getEffective()
```

Получает данные эффекта Glow с применённым наследованием.

**Возвращаемое значение:**
[IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata) - A [IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata).
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

Определяет, равен ли указанный [Glow](../../com.aspose.slides/glow) текущему [Glow](../../com.aspose.slides/glow).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | The [Glow](../../com.aspose.slides/glow) to compare. |

**Возвращаемое значение:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Служит хэш-функцией для определённого типа.

**Возвращаемое значение:**
int - A hash code for the current object.