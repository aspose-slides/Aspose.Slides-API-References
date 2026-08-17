---
title: Glow
second_title: Справочник API Aspose.Slides для Java
description: Представляет эффект свечения, при котором размытая цветная обводка добавляется за пределами краев объекта.
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

Представляет эффект свечения, при котором размытая цветная обводка добавляется за пределами краев объекта.
## Методы

| Метод | Описание |
| --- | --- |
| [getRadius()](#getRadius--) | Radius. |
| [setRadius(double value)](#setRadius-double-) | Radius. |
| [getColor()](#getColor--) | Color format. |
| [getEffective()](#getEffective--) | Получает эффективные данные эффекта Glow с применённым наследованием. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный [Glow](../../com.aspose.slides/glow) текущему [Glow](../../com.aspose.slides/glow). |
| [hashCode()](#hashCode--) | Служит хеш-функцией для конкретного типа. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```


Radius. Чтение/запись double .

**Возвращаемое значение:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```


Radius. Чтение/запись double .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```


Color format. Только чтение [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращаемое значение:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IGlowEffectiveData getEffective()
```


Получает эффективные данные эффекта Glow с применённым наследованием.

**Возвращаемое значение:**
[IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata) - [IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Возвращает объект Parent_Immediate. Только чтение IDOMObject.

**Возвращаемое значение:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Version. Только чтение long.

**Возвращаемое значение:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


Возвращает родительский IPresentationComponent. Только чтение [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

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
| obj | java.lang.Object | Объект [Glow](../../com.aspose.slides/glow) для сравнения. |

**Возвращаемое значение:**
boolean - true если объекты равны; иначе false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Служит хеш-функцией для конкретного типа.

**Возвращаемое значение:**
int - Хеш-код текущего объекта.