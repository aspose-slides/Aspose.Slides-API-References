---
title: HSL
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет эффект Hue/Saturation/Luminance.
type: docs
url: /ru/com.aspose.slides/hsl/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Все реализованные интерфейсы:**
[com.aspose.slides.IHSL](../../com.aspose.slides/ihsl), com.aspose.slides.IVisualEffect
```
public final class HSL extends ImageTransformOperation implements IHSL, IVisualEffect
```

Представляет эффект Hue/Saturation/Luminance. Оттенок, насыщенность и яркость могут быть скорректированы относительно их текущих значений.
## Методы

| Метод | Описание |
| --- | --- |
| [getEffective()](#getEffective--) | Получает эффективные данные эффекта Hue/Saturation/Luminance с применённым наследованием. |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный [HSL](../../com.aspose.slides/hsl) текущему [HSL](../../com.aspose.slides/hsl). |
| [hashCode()](#hashCode--) | Служит в качестве функции хеширования для конкретного типа. |
### getEffective() {#getEffective--}
```
public final IHSLEffectiveData getEffective()
```


Получает эффективные данные эффекта Hue/Saturation/Luminance с применённым наследованием.

**Возвращаемое значение:**
[IHSLEffectiveData](../../com.aspose.slides/ihsleffectivedata) - [IHSLEffectiveData](../../com.aspose.slides/ihsleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равен ли указанный [HSL](../../com.aspose.slides/hsl) текущему [HSL](../../com.aspose.slides/hsl).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект [HSL](../../com.aspose.slides/hsl) для сравнения. |

**Возвращаемое значение:**
boolean - true, если объекты равны; иначе false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Служит в качестве функции хеширования для конкретного типа.

**Возвращаемое значение:**
int - Хеш-код для текущего объекта.