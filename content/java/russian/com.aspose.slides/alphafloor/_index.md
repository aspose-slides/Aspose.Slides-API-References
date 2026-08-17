---
title: AlphaFloor
second_title: Aspose.Slides для справочника API Java
description: Представляет эффект Alpha Floor.
type: docs
url: /ru/com.aspose.slides/alphafloor/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Все реализованные интерфейсы:**
[com.aspose.slides.IAlphaFloor](../../com.aspose.slides/ialphafloor), com.aspose.slides.IVisualEffect
```
public final class AlphaFloor extends ImageTransformOperation implements IAlphaFloor, IVisualEffect
```

Представляет эффект Alpha Floor. Значения Alpha (непрозрачность) меньше 100% изменяются на ноль. Другими словами, всё частично прозрачное становится полностью прозрачным.
## Методы

| Method | Description |
| --- | --- |
| [getEffective()](#getEffective--) | Получает эффективные данные эффекта Alpha Floor с учётом наследования. |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный [AlphaFloor](../../com.aspose.slides/alphafloor) текущему [AlphaFloor](../../com.aspose.slides/alphafloor). |
| [hashCode()](#hashCode--) | Служит в качестве хеш-функции для определённого типа. |
### getEffective() {#getEffective--}
```
public final IAlphaFloorEffectiveData getEffective()
```

Получает эффективные данные эффекта Alpha Floor с учётом наследования.

**Возвращаемое значение:**
[IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata) - Экземпляр [IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Определяет, равен ли указанный [AlphaFloor](../../com.aspose.slides/alphafloor) текущему [AlphaFloor](../../com.aspose.slides/alphafloor).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект [AlphaFloor](../../com.aspose.slides/alphafloor) для сравнения. |

**Возвращаемое значение:**
boolean - true если объекты равны; иначе false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Служит в качестве хеш-функции для определённого типа.

**Возвращаемое значение:**
int - Хеш-код для текущего объекта.