---
title: Duotone
second_title: Aspose.Slides для Android через справочник Java API
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

Представляет эффект Дуотон. Для каждого пикселя сочетает Color1 и Color2 посредством линейной интерполяции, чтобы определить новый цвет для этого пикселя.
## Методы

| Метод | Описание |
| --- | --- |
| [getColor1()](#getColor1--) | Возвращает целевой формат цвета для тёмных пикселей. |
| [getColor2()](#getColor2--) | Возвращает целевой формат цвета для светлых пикселей. |
| [getEffective()](#getEffective--) | Получает эффективные данные эффекта Дуотон с учётом наследования. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный [Duotone](../../com.aspose.slides/duotone) текущему [Duotone](../../com.aspose.slides/duotone). |
| [hashCode()](#hashCode--) | Служит хеш-функцией для конкретного типа. |
### getColor1() {#getColor1--}
```
public final IColorFormat getColor1()
```


Возвращает целевой формат цвета для тёмных пикселей. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращаемое значение:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getColor2() {#getColor2--}
```
public final IColorFormat getColor2()
```


Возвращает целевой формат цвета для светлых пикселей. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращаемое значение:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IDuotoneEffectiveData getEffective()
```


Получает эффективные данные эффекта Дуотон с учётом наследования.

**Возвращаемое значение:**
[IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata) - Объект [IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata).
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


Определяет, равен ли указанный [Duotone](../../com.aspose.slides/duotone) текущему [Duotone](../../com.aspose.slides/duotone).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект [Duotone](../../com.aspose.slides/duotone) для сравнения. |

**Возвращаемое значение:**
boolean - true если объекты равны; в противном случае false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Служит хеш-функцией для конкретного типа.

**Возвращаемое значение:**
int - Хеш-код текущего объекта.