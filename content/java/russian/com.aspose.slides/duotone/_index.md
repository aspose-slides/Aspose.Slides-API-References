---
title: Duotone
second_title: Справочник API Aspose.Slides для Java
description: Представляет эффект Duotone.
type: docs
url: /ru/com.aspose.slides/duotone/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Все реализованные интерфейсы:**
[com.aspose.slides.IDuotone](../../com.aspose.slides/iduotone), com.aspose.slides.IVisualEffect
```
public final class Duotone extends ImageTransformOperation implements IDuotone, IVisualEffect
```

Представляет эффект Duotone. Для каждого пикселя комбинирует Color1 и Color2 посредством линейной интерполяции, чтобы определить новый цвет пикселя.
## Методы

| Метод | Описание |
| --- | --- |
| [getColor1()](#getColor1--) | Возвращает целевой цветовой формат для тёмных пикселей. |
| [getColor2()](#getColor2--) | Возвращает целевой цветовой формат для светлых пикселей. |
| [getEffective()](#getEffective--) | Получает эффективные данные эффекта Duotone с учётом наследования. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный [Duotone](../../com.aspose.slides/duotone) текущему [Duotone](../../com.aspose.slides/duotone). |
| [hashCode()](#hashCode--) | Служит хеш-функцией для определённого типа. |
### getColor1() {#getColor1--}
```
public final IColorFormat getColor1()
```


Возвращает целевой цветовой формат для тёмных пикселей. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращает:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getColor2() {#getColor2--}
```
public final IColorFormat getColor2()
```


Возвращает целевой цветовой формат для светлых пикселей. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращает:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IDuotoneEffectiveData getEffective()
```


Получает эффективные данные эффекта Duotone с учётом наследования.

**Возвращает:**
[IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata) - A [IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata).
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


Определяет, равен ли указанный [Duotone](../../com.aspose.slides/duotone) текущему [Duotone](../../com.aspose.slides/duotone).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект [Duotone](../../com.aspose.slides/duotone) для сравнения. |

**Возвращает:**
boolean - true, если объекты равны; иначе false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Служит хеш-функцией для определённого типа.

**Возвращает:**
int - хеш-код текущего объекта.