---
title: BiLevel
second_title: Справочник API Aspose.Slides для Java
description: Представляет двухуровневый (чёрно-белый) эффект.
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

Представляет двухуровневый (чёрно-белый) эффект. Цвета входных данных, у которых яркость меньше указанного порогового значения, преобразуются в чёрный. Цвета, у которых яркость больше или равна указанному значению, устанавливаются в белый. Значения альфа-эффекта не изменяются этим эффектом.
## Методы

| Метод | Описание |
| --- | --- |
| [getEffective()](#getEffective--) | Gets effective Bi-Level effect data with the inheritance applied. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [BiLevel](../../com.aspose.slides/bilevel) is equal to the current [BiLevel](../../com.aspose.slides/bilevel). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### getEffective() {#getEffective--}
```
public final IBiLevelEffectiveData getEffective()
```

Получает эффективные данные двухуровневого эффекта с учётом наследования.

**Возвращаемое значение:**
[IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata) — [IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Определяет, равен ли указанный [BiLevel](../../com.aspose.slides/bilevel) текущему [BiLevel](../../com.aspose.slides/bilevel).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | [BiLevel](../../com.aspose.slides/bilevel) для сравнения. |

**Возвращаемое значение:**
boolean — true, если объекты равны; иначе false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Используется в качестве хеш-функции для определённого типа.

**Возвращаемое значение:**
int — хеш-код текущего объекта.