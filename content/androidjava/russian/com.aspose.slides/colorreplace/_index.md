---
title: ColorReplace
second_title: Aspose.Slides для Android через справочник Java API
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

Представляет эффект Color Replacement. Все цвета эффекта изменяются на фиксированный цвет. Значения альфа не затрагиваются.
## Методы

| Method | Description |
| --- | --- |
| [getColor()](#getColor--) | Возвращает формат цвета, который заменит цвет каждого пикселя. |
| [getEffective()](#getEffective--) | Получает эффективные данные эффекта Color Replacement с применённым наследованием. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный [ColorReplace](../../com.aspose.slides/colorreplace) текущему [ColorReplace](../../com.aspose.slides/colorreplace). |
| [hashCode()](#hashCode--) | Служит в качестве хеш-функции для определённого типа. |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

Возвращает формат цвета, который заменит цвет каждого пикселя. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращает:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorReplaceEffectiveData getEffective()
```

Получает эффективные данные эффекта Color Replacement с применённым наследованием.

**Возвращает:**
[IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata) — объект [IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Версия. Только для чтения long.

**Возвращает:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Определяет, равен ли указанный [ColorReplace](../../com.aspose.slides/colorreplace) текущему [ColorReplace](../../com.aspose.slides/colorreplace).

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | [ColorReplace](../../com.aspose.slides/colorreplace) для сравнения. |

**Возвращает:**
boolean — true, если объекты равны; иначе — false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Служит в качестве хеш-функции для определённого типа.

**Возвращает:**
int — Хеш-код текущего объекта.