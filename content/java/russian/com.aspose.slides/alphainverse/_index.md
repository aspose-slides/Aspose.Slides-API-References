---
title: AlphaInverse
second_title: Справочник API Aspose.Slides для Java
description: Представляет эффект инверсии альфа.
type: docs
url: /ru/com.aspose.slides/alphainverse/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Все реализованные интерфейсы:**
[com.aspose.slides.IAlphaInverse](../../com.aspose.slides/ialphainverse), com.aspose.slides.IVisualEffect
```
public final class AlphaInverse extends ImageTransformOperation implements IAlphaInverse, IVisualEffect
```

Представляет эффект инверсии альфа-канала. Значения альфа (непрозрачности) инвертируются вычитанием из 100 %.

## Методы

| Method | Description |
| --- | --- |
| [getEffective()](#getEffective--) | Получает эффективные данные эффекта инверсии альфа с учётом наследования. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равно ли указанное [AlphaInverse](../../com.aspose.slides/alphainverse) текущему [AlphaInverse](../../com.aspose.slides/alphainverse). |
| [hashCode()](#hashCode--) | Служит хеш-функцией для конкретного типа. |

### getEffective() {#getEffective--}
```
public final IAlphaInverseEffectiveData getEffective()
```

Получает эффективные данные эффекта инверсии альфа с учётом наследования.

**Возвращаемое значение:**
[IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata) - A [IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata).

### getVersion() {#getVersion--}
```
public long getVersion()
```

Версия. Только для чтения long.

**Возвращаемое значение:**
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Определяет, равно ли указанное [AlphaInverse](../../com.aspose.slides/alphainverse) текущему [AlphaInverse](../../com.aspose.slides/alphainverse).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | The [AlphaInverse](../../com.aspose.slides/alphainverse) to compare. |

**Возвращаемое значение:**
boolean - true if objects are equal; otherwise, false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Служит хеш-функцией для конкретного типа.

**Возвращаемое значение:**
int - A hash code for the current object.