---
title: Blur
second_title: Справочник API Aspose.Slides для Java
description: Представляет эффект размытия, применяемый ко всей фигуре, включая её заливку.
type: docs
url: /ru/com.aspose.slides/blur/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Все реализованные интерфейсы:**
[com.aspose.slides.IBlur](../../com.aspose.slides/iblur), com.aspose.slides.IVisualEffect
```
public final class Blur extends ImageTransformOperation implements IBlur, IVisualEffect
```

Представляет эффект размытия, применяемый ко всей фигуре, включая её заливку. Все цветовые каналы, включая альфу, затронуты.
## Методы

| Метод | Описание |
| --- | --- |
| [getRadius()](#getRadius--) | Возвращает или задает радиус размытия. |
| [setRadius(double value)](#setRadius-double-) | Возвращает или задает радиус размытия. |
| [getGrow()](#getGrow--) | Определяет, должны ли границы объекта увеличиваться в результате размытия. |
| [setGrow(boolean value)](#setGrow-boolean-) | Определяет, должны ли границы объекта увеличиваться в результате размытия. |
| [getEffective()](#getEffective--) | Получает эффективные данные эффекта размытия с применённым наследованием. |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный [Blur](../../com.aspose.slides/blur) текущему [Blur](../../com.aspose.slides/blur). |
| [hashCode()](#hashCode--) | Служит хеш-функцией для определённого типа. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```

Возвращает или задает радиус размытия. Чтение/запись double.

**Возвращаемое значение:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

Возвращает или задает радиус размытия. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |
### getGrow() {#getGrow--}
```
public final boolean getGrow()
```

Определяет, должны ли границы объекта увеличиваться в результате размытия. Значение true указывает, что границы увеличены, а false — что они не увеличены. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public final void setGrow(boolean value)
```

Определяет, должны ли границы объекта увеличиваться в результате размытия. Значение true указывает, что границы увеличены, а false — что они не увеличены. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getEffective() {#getEffective--}
```
public final IBlurEffectiveData getEffective()
```

Получает эффективные данные эффекта размытия с применённым наследованием.

**Возвращаемое значение:**
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata) - [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Определяет, равен ли указанный [Blur](../../com.aspose.slides/blur) текущему [Blur](../../com.aspose.slides/blur).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект [Blur](../../com.aspose.slides/blur) для сравнения. |

**Возвращаемое значение:**
boolean - true если объекты равны; иначе false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Служит хеш-функцией для определённого типа.

**Возвращаемое значение:**
int - Хеш-код для текущего объекта.