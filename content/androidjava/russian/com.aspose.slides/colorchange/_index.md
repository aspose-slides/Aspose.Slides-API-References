---
title: ColorChange
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет эффект изменения цвета.
type: docs
url: /ru/com.aspose.slides/colorchange/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Все реализованные интерфейсы:**
[com.aspose.slides.IColorChange](../../com.aspose.slides/icolorchange), com.aspose.slides.IVisualEffect
```
public final class ColorChange extends ImageTransformOperation implements IColorChange, IVisualEffect
```

Представляет эффект изменения цвета. Экземпляры FromColor заменяются экземплярами ToColor.
## Методы

| Метод | Описание |
| --- | --- |
| [getFromColor()](#getFromColor--) | Цвет, который будет заменён. |
| [getToColor()](#getToColor--) | Цвет, который заменит. |
| [getEffective()](#getEffective--) | Получает эффективные данные эффекта изменения цвета с учётом наследования. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный [ColorChange](../../com.aspose.slides/colorchange) текущему [ColorChange](../../com.aspose.slides/colorchange). |
| [hashCode()](#hashCode--) | Служит в качестве хеш-функции для конкретного типа. |
### getFromColor() {#getFromColor--}
```
public final IColorFormat getFromColor()
```


Цвет, который будет заменён. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращает:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public final IColorFormat getToColor()
```


Цвет, который заменит. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращает:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorChangeEffectiveData getEffective()
```


Получает эффективные данные эффекта изменения цвета с учётом наследования.

**Возвращает:**
[IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata) - A [IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata).
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


Определяет, равен ли указанный [ColorChange](../../com.aspose.slides/colorchange) текущему [ColorChange](../../com.aspose.slides/colorchange).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | [ColorChange](../../com.aspose.slides/colorchange) для сравнения. |

**Возвращает:**
boolean - true, если объекты равны; иначе false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Служит в качестве хеш-функции для конкретного типа.

**Возвращает:**
int — хеш-код текущего объекта.