---
title: Blur
second_title: Aspose.Slides для Android через Java API
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

Представляет эффект размытия, применяемый ко всей фигуре, включая её заливку. Все цветовые каналы, включая альфа-канал, затрагиваются.
## Методы

| Метод | Описание |
| --- | --- |
| [getRadius()](#getRadius--) | Возвращает или задает радиус размытия. |
| [setRadius(double value)](#setRadius-double-) | Возвращает или задает радиус размытия. |
| [getGrow()](#getGrow--) | Определяет, следует ли увеличивать границы объекта в результате размытия. |
| [setGrow(boolean value)](#setGrow-boolean-) | Определяет, следует ли увеличивать границы объекта в результате размытия. |
| [getEffective()](#getEffective--) | Получает эффективные данные эффекта Blur с учётом наследования. |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный [Blur](../../com.aspose.slides/blur) текущему [Blur](../../com.aspose.slides/blur). |
| [hashCode()](#hashCode--) | Служит хеш-функцией для конкретного типа. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```

Возвращает или задает радиус размытия. Чтение/запись double.

**Возвращает:**
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

Определяет, следует ли увеличивать границы объекта в результате размытия. True указывает, что границы увеличиваются, а false — что нет. Чтение/запись boolean.

**Возвращает:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public final void setGrow(boolean value)
```

Определяет, следует ли увеличивать границы объекта в результате размытия. True указывает, что границы увеличиваются, а false — что нет. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getEffective() {#getEffective--}
```
public final IBlurEffectiveData getEffective()
```

Получает эффективные данные эффекта Blur с учётом наследования.

**Возвращает:**
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata) - [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Определяет, равен ли указанный [Blur](../../com.aspose.slides/blur) текущему [Blur](../../com.aspose.slides/blur).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | [Blur](../../com.aspose.slides/blur) для сравнения. |

**Возвращает:**
boolean - true, если объекты равны; иначе false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Служит хеш-функцией для конкретного типа.

**Возвращает:**
int - Хеш-код текущего объекта.