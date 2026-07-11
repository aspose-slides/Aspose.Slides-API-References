---
title: AlphaFloor
second_title: Aspose.Slides для Android через справочник Java API
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

Представляет эффект Alpha Floor. Значения альфа (непрозрачности) менее 100 % изменяются на ноль. Другими словами, всё частично прозрачное становится полностью прозрачным.

## Методы

| Метод | Описание |
| --- | --- |
| [getEffective()](#getEffective--) | Получает данные эффективного эффекта Alpha Floor с применённым наследованием. |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный [AlphaFloor](../../com.aspose.slides/alphafloor) текущему [AlphaFloor](../../com.aspose.slides/alphafloor). |
| [hashCode()](#hashCode--) | Служит хеш-функцией для конкретного типа. |

### getEffective() {#getEffective--}
```
public final IAlphaFloorEffectiveData getEffective()
```

Получает данные эффективного эффекта Alpha Floor с применённым наследованием.

**Возвращаемое значение:**
[IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata) - это [IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Определяет, равен ли указанный [AlphaFloor](../../com.aspose.slides/alphafloor) текущему [AlphaFloor](../../com.aspose.slides/alphafloor).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | [AlphaFloor](../../com.aspose.slides/alphafloor) для сравнения. |

**Возвращаемое значение:**
boolean - true if objects are equal; otherwise, false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Служит хеш-функцией для конкретного типа.

**Возвращаемое значение:**
int - Хеш-код для текущего объекта.