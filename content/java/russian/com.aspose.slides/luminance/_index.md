---
title: Luminance
second_title: Справочник API Aspose.Slides для Java
description: Представляет эффект Luminance.
type: docs
url: /ru/com.aspose.slides/luminance/
---
**Наследование:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Все реализованные интерфейсы:**  
[com.aspose.slides.ILuminance](../../com.aspose.slides/iluminance), com.aspose.slides.IVisualEffect  
```
public final class Luminance extends ImageTransformOperation implements ILuminance, IVisualEffect
```

Представляет эффект Luminance. Brightness линейно сдвигает все цвета ближе к белому или черному. Contrast масштабирует все цвета так, чтобы они были либо ближе, либо дальше друг от друга.

## Методы

| Метод | Описание |
| --- | --- |
| [getEffective()](#getEffective--) | Gets effective Luminance effect data with the inheritance applied. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [Luminance](../../com.aspose.slides/luminance) is equal to the current [Luminance](../../com.aspose.slides/luminance). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |

### getEffective() {#getEffective--}
```
public final ILuminanceEffectiveData getEffective()
```

Получает эффективные данные эффекта Luminance с применённым наследованием.

**Возвращаемое значение:**  
[ILuminanceEffectiveData](../../com.aspose.slides/iluminanceeffectivedata) - Объект [ILuminanceEffectiveData](../../com.aspose.slides/iluminanceeffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Определяет, равен ли указанный [Luminance](../../com.aspose.slides/luminance) текущему [Luminance](../../com.aspose.slides/luminance).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | [Luminance](../../com.aspose.slides/luminance) для сравнения. |

**Возвращаемое значение:**  
boolean - true если объекты равны; иначе false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Служит хеш-функцией для конкретного типа.

**Возвращаемое значение:**  
int - Хеш-код текущего объекта.