---
title: AlphaInverse
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет эффект Alpha Inverse.
type: docs
url: /ru/com.aspose.slides/alphainverse/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**
[com.aspose.slides.IAlphaInverse](../../com.aspose.slides/ialphainverse), com.aspose.slides.IVisualEffect
```
public final class AlphaInverse extends ImageTransformOperation implements IAlphaInverse, IVisualEffect
```

Represents an Alpha Inverse effect. Alpha (opacity) values are inverted by subtracting from 100%.
## Методы

| Метод | Описание |
| --- | --- |
| [getEffective()](#getEffective--) | Gets effective Alpha Inverse effect data with the inheritance applied. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [AlphaInverse](../../com.aspose.slides/alphainverse) is equal to the current [AlphaInverse](../../com.aspose.slides/alphainverse). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### getEffective() {#getEffective--}
```
public final IAlphaInverseEffectiveData getEffective()
```

Получает данные эффективного эффекта Alpha Inverse с применённым наследованием.

**Возвращаемое значение:**
[IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata) - A [IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Только для чтения long.

**Возвращаемое значение:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Определяет, равен ли указанный [AlphaInverse](../../com.aspose.slides/alphainverse) текущему [AlphaInverse](../../com.aspose.slides/alphainverse).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект [AlphaInverse](../../com.aspose.slides/alphainverse) для сравнения. |

**Возвращаемое значение:**
boolean - true, если объекты равны; иначе — false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Служит хеш-функцией для определённого типа.

**Возвращаемое значение:**
int - Хеш-код текущего объекта.