---
title: ColorReplace
second_title: Справочник API Aspose.Slides для Java
description: Представляет эффект замены цвета.
type: docs
url: /ru/com.aspose.slides/colorreplace/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Все реализованные интерфейсы:**
[com.aspose.slides.IColorReplace](../../com.aspose.slides/icolorreplace), com.aspose.slides.IVisualEffect, java.lang.Cloneable
```
public final class ColorReplace extends ImageTransformOperation implements IColorReplace, IVisualEffect, Cloneable
```

Представляет эффект замены цвета. Все цвета эффекта заменяются фиксированным цветом. Значения альфа остаются неизменными.
## Методы

| Метод | Описание |
| --- | --- |
| [getColor()](#getColor--) | Возвращает формат цвета, который заменит цвет каждого пикселя. |
| [getEffective()](#getEffective--) | Получает эффективные данные эффекта замены цвета с применённым наследованием. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный [ColorReplace](../../com.aspose.slides/colorreplace) текущему [ColorReplace](../../com.aspose.slides/colorreplace). |
| [hashCode()](#hashCode--) | Служит хэш-функцией для определённого типа. |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

Возвращает формат цвета, который заменит цвет каждого пикселя. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращаемое значение:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorReplaceEffectiveData getEffective()
```

Получает эффективные данные эффекта замены цвета с применённым наследованием.

**Возвращаемое значение:**
[IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata) - A [IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata).
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

Определяет, равен ли указанный [ColorReplace](../../com.aspose.slides/colorreplace) текущему [ColorReplace](../../com.aspose.slides/colorreplace).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | The [ColorReplace](../../com.aspose.slides/colorreplace) to compare. |

**Возвращаемое значение:**
boolean - true, если объекты равны; иначе false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Служит хэш-функцией для определённого типа.

**Возвращаемое значение:**
int - Хеш-код для текущего объекта.