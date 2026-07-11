---
title: BiLevel
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет двууровневый черно-белый эффект.
type: docs
url: /ru/com.aspose.slides/bilevel/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Все реализованные интерфейсы:**
[com.aspose.slides.IBiLevel](../../com.aspose.slides/ibilevel), com.aspose.slides.IVisualEffect
```
public final class BiLevel extends ImageTransformOperation implements IBiLevel, IVisualEffect
```

Представляет эффект двууровневой (чёрно-белой) обработки. Входные цвета, чья яркость меньше указанного порогового значения, изменяются на чёрный. Входные цвета, чья яркость больше или равна указанному значению, устанавливаются в белый. Значения альфа-эффекта не изменяются этим эффектом.
## Методы

| Метод | Описание |
| --- | --- |
| [getEffective()](#getEffective--) | Получает эффективные данные эффекта Bi-Level с учётом наследования. |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный [BiLevel](../../com.aspose.slides/bilevel) текущему [BiLevel](../../com.aspose.slides/bilevel). |
| [hashCode()](#hashCode--) | Служит хеш-функцией для определённого типа. |
### getEffective() {#getEffective--}
```
public final IBiLevelEffectiveData getEffective()
```

Получает эффективные данные эффекта Bi-Level с учётом наследования.

**Возвращаемое значение:**
[IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata) - [IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Определяет, равно ли указанное [BiLevel](../../com.aspose.slides/bilevel) текущему [BiLevel](../../com.aspose.slides/bilevel).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | [BiLevel](../../com.aspose.slides/bilevel) для сравнения. |

**Возвращаемое значение:**
boolean - true, если объекты равны; иначе false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Служит хеш-функцией для определённого типа.

**Возвращаемое значение:**
int - хеш-код текущего объекта.