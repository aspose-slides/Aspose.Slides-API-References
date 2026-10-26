---
title: AlphaBiLevel
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет эффект Alpha Bi-Level.
type: docs
url: /ru/com.aspose.slides/alphabilevel/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Все реализованные интерфейсы:**
[com.aspose.slides.IAlphaBiLevel](../../com.aspose.slides/ialphabilevel), com.aspose.slides.IVisualEffect
```
public final class AlphaBiLevel extends ImageTransformOperation implements IAlphaBiLevel, IVisualEffect
```

Представляет эффект Alpha Bi-Level. Значения Alpha (Opacity) ниже порога изменяются на 0 (полностью прозрачные), а значения alpha, превышающие или равные порогу, изменяются на 100 % (полностью непрозрачные).
## Методы

| Метод | Описание |
| --- | --- |
| [getThreshold()](#getThreshold--) | Возвращает порог эффекта. |
| [setThreshold(float value)](#setThreshold-float-) | Возвращает порог эффекта. |
| [getEffective()](#getEffective--) | Получает данные эффективного эффекта Alpha Bi-Level с учётом наследования. |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный [AlphaBiLevel](../../com.aspose.slides/alphabilevel) текущему [AlphaBiLevel](../../com.aspose.slides/alphabilevel). |
| [hashCode()](#hashCode--) | Служит хеш-функцией для конкретного типа. |
### getThreshold() {#getThreshold--}
```
public final float getThreshold()
```


Возвращает порог эффекта. Чтение/запись float.

**Возвращает:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public final void setThreshold(float value)
```


Возвращает порог эффекта. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final IAlphaBiLevelEffectiveData getEffective()
```


Получает данные эффективного эффекта Alpha Bi-Level с учётом наследования.

**Возвращает:**
[IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata) - A [IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равен ли указанный [AlphaBiLevel](../../com.aspose.slides/alphabilevel) текущему [AlphaBiLevel](../../com.aspose.slides/alphabilevel).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | [AlphaBiLevel](../../com.aspose.slides/alphabilevel) для сравнения. |

**Возвращает:**
boolean - true если объекты равны; иначе false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Служит хеш-функцией для конкретного типа.

**Возвращает:**
int - Хеш-код для текущего объекта.