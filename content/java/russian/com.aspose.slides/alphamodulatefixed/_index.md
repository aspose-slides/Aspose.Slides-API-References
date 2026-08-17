---
title: AlphaModulateFixed
second_title: Aspose.Slides для Java: справочник API
description: Представляет фиксированный эффект модуляции альфа.
type: docs
url: /ru/com.aspose.slides/alphamodulatefixed/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Все реализованные интерфейсы:**
[com.aspose.slides.IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed), com.aspose.slides.IVisualEffect
```
public final class AlphaModulateFixed extends ImageTransformOperation implements IAlphaModulateFixed, IVisualEffect
```

Представляет фиксированный эффект модуляции альфа. Значения альфа-эффекта (непрозрачности) умножаются на фиксированный процент.
## Методы

| Метод | Описание |
| --- | --- |
| [getAmount()](#getAmount--) | Возвращает величину эффекта в процентах. |
| [setAmount(float value)](#setAmount-float-) | Возвращает величину эффекта в процентах. |
| [getEffective()](#getEffective--) | Получает данные эффекта Alpha Modulate Fixed с учётом наследования. |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed) текущему [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed). |
| [hashCode()](#hashCode--) | Служит хеш-функцией для определенного типа. |
### getAmount() {#getAmount--}
```
public final float getAmount()
```

Возвращает величину эффекта в процентах. Чтение/запись float.

**Возвращаемое значение:**
float
### setAmount(float value) {#setAmount-float-}
```
public final void setAmount(float value)
```

Возвращает величину эффекта в процентах. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public final IAlphaModulateFixedEffectiveData getEffective()
```

Получает данные эффекта Alpha Modulate Fixed с учётом наследования.

**Возвращаемое значение:**
[IAlphaModulateFixedEffectiveData](../../com.aspose.slides/ialphamodulatefixedeffectivedata) - объект [IAlphaModulateFixedEffectiveData](../../com.aspose.slides/ialphamodulatefixedeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Определяет, равен ли указанный [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed) текущему [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed) для сравнения. |

**Возвращаемое значение:**
boolean — true, если объекты равны; иначе false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Служит хеш-функцией для определенного типа.

**Возвращаемое значение:**
int — хеш-код текущего объекта.