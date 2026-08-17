---
title: SoftEdge
second_title: Справочник API Aspose.Slides для Java
description: Представляет эффект мягкой кромки.
type: docs
url: /ru/com.aspose.slides/softedge/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.ISoftEdge](../../com.aspose.slides/isoftedge), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class SoftEdge implements ISoftEdge, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Представляет эффект мягкой кромки. Края фигуры размыты, в то время как заливка не затронута.

## Методы

| Метод | Описание |
| --- | --- |
| [getRadius()](#getRadius--) | Указывает радиус размытия, применяемый к краям. |
| [setRadius(double value)](#setRadius-double-) | Указывает радиус размытия, применяемый к краям. |
| [getEffective()](#getEffective--) | Получает эффективные данные эффекта Soft Edge с применением наследования. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный [SoftEdge](../../com.aspose.slides/softedge) текущему [SoftEdge](../../com.aspose.slides/softedge). |
| [hashCode()](#hashCode--) | Служит в качестве функции хеширования для определенного типа. |

### getRadius() {#getRadius--}
```
public final double getRadius()
```

Указывает радиус размытия, применяемый к краям. Чтение/запись double.

**Возвращаемое значение:**
double

### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

Указывает радиус размытия, применяемый к краям. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getEffective() {#getEffective--}
```
public final ISoftEdgeEffectiveData getEffective()
```

Получает эффективные данные эффекта Soft Edge с применением наследования.

**Возвращаемое значение:**
[ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata) - A [ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata).

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

Версия. Только чтение long.

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

Определяет, равен ли указанный [SoftEdge](../../com.aspose.slides/softedge) текущему [SoftEdge](../../com.aspose.slides/softedge).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | The [SoftEdge](../../com.aspose.slides/softedge) to compare. |

**Возвращаемое значение:**
boolean - true if objects are equal; otherwise, false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Служит в качестве функции хеширования для определенного типа.

**Возвращаемое значение:**
int - A hash code for the current object.