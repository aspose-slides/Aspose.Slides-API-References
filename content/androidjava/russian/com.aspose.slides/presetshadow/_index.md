---
title: PresetShadow
second_title: Aspose.Slides для Android через Java API
description: Представляет эффект Preset Shadow.
type: docs
url: /ru/com.aspose.slides/presetshadow/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IPresetShadow](../../com.aspose.slides/ipresetshadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class PresetShadow implements IPresetShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Представляет эффект Preset Shadow.
## Методы

| Метод | Описание |
| --- | --- |
| [getDirection()](#getDirection--) | Направление тени. |
| [setDirection(float value)](#setDirection-float-) | Направление тени. |
| [getDistance()](#getDistance--) | Расстояние тени. |
| [setDistance(double value)](#setDistance-double-) | Расстояние тени. |
| [getShadowColor()](#getShadowColor--) | Цвет тени. |
| [getPreset()](#getPreset--) | Preset. |
| [setPreset(int value)](#setPreset-int-) | Preset. |
| [getEffective()](#getEffective--) | Получает эффективные данные эффекта Preset Shadow с применённым наследованием. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный [PresetShadow](../../com.aspose.slides/presetshadow) текущему [PresetShadow](../../com.aspose.slides/presetshadow). |
| [hashCode()](#hashCode--) | Служит хеш-функцией для конкретного типа. |
### getDirection() {#getDirection--}
```
public final float getDirection()
```

Направление тени. Чтение/запись float.

**Возвращаемое значение:**
float
### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

Направление тени. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public final double getDistance()
```

Расстояние тени. Чтение/запись double.

**Возвращаемое значение:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

Расстояние тени. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```

Цвет тени. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращаемое значение:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public final int getPreset()
```

Preset. Чтение/запись [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Возвращаемое значение:**
int
### setPreset(int value) {#setPreset-int-}
```
public final void setPreset(int value)
```

Preset. Чтение/запись [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public final IPresetShadowEffectiveData getEffective()
```

Получает эффективные данные эффекта Preset Shadow с применённым наследованием.

**Возвращаемое значение:**
[IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata) - A [IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Возвращает объект Parent_Immediate. Только для чтения IDOMObject.

**Возвращаемое значение:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

Версия. Только для чтения long.

**Возвращаемое значение:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Возвращает родительский IPresentationComponent. Только для чтения [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Возвращаемое значение:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Определяет, равен ли указанный [PresetShadow](../../com.aspose.slides/presetshadow) текущему [PresetShadow](../../com.aspose.slides/presetshadow).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | [PresetShadow](../../com.aspose.slides/presetshadow) для сравнения. |

**Возвращаемое значение:**
boolean - true если объекты равны; иначе false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Служит хеш-функцией для конкретного типа.

**Возвращаемое значение:**
int - Хеш-код текущего объекта.