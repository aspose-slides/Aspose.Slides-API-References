---
title: GrayScale
second_title: Aspose.Slides для справки по Java API
description: Представляет эффект Gray Scale.
type: docs
url: /ru/com.aspose.slides/grayscale/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Все реализованные интерфейсы:**
[com.aspose.slides.IGrayScale](../../com.aspose.slides/igrayscale), com.aspose.slides.IVisualEffect
```
public final class GrayScale extends ImageTransformOperation implements IGrayScale, IVisualEffect
```

Представляет эффект Gray Scale. Преобразует все значения цветов эффекта в оттенок серого, соответствующий их яркости. Значения альфа-канала (opacity) эффекта не изменяются.
## Методы

| Метод | Описание |
| --- | --- |
| [getEffective()](#getEffective--) | Gets effective Gray Scale effect data with the inheritance applied. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [GrayScale](../../com.aspose.slides/grayscale) is equal to the current [GrayScale](../../com.aspose.slides/grayscale). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### getEffective() {#getEffective--}
```
public final IGrayScaleEffectiveData getEffective()
```

Получает эффективные данные эффекта Gray Scale с примененным наследованием.

**Возвращаемое значение:**
[IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata) - Экземпляр [IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Определяет, равен ли указанный [GrayScale](../../com.aspose.slides/grayscale) текущему [GrayScale](../../com.aspose.slides/grayscale).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект [GrayScale](../../com.aspose.slides/grayscale) для сравнения. |

**Возвращаемое значение:**
boolean - true, если объекты равны; иначе — false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Служит хеш-функцией для конкретного типа.

**Возвращаемое значение:**
int - Хеш-код текущего объекта.