---
title: ColorChange
second_title: Справочник API Aspose.Slides для Java
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
| [getFromColor()](#getFromColor--) | Цвет, который будет заменен. |
| [getToColor()](#getToColor--) | Цвет, который заменит. |
| [getEffective()](#getEffective--) | Получает эффективные данные эффекта изменения цвета с учётом наследования. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный [ColorChange](../../com.aspose.slides/colorchange) текущему [ColorChange](../../com.aspose.slides/colorchange). |
| [hashCode()](#hashCode--) | Служит хеш-функцией для определённого типа. |
### getFromColor() {#getFromColor--}
```
public final IColorFormat getFromColor()
```


Цвет, который будет заменен. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращаемое значение:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public final IColorFormat getToColor()
```


Цвет, который заменит. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращаемое значение:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorChangeEffectiveData getEffective()
```


Получает эффективные данные эффекта изменения цвета с учётом наследования.

**Возвращаемое значение:**
[IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata) - [IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata).
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


Определяет, равен ли указанный [ColorChange](../../com.aspose.slides/colorchange) текущему [ColorChange](../../com.aspose.slides/colorchange).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект [ColorChange](../../com.aspose.slides/colorchange) для сравнения. |

**Возвращаемое значение:**
boolean - true если объекты равны; иначе false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Служит хеш-функцией для определённого типа.

**Возвращаемое значение:**
int - Хеш-код для текущего объекта.