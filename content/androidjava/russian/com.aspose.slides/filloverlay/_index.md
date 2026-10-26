---
title: FillOverlay
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет эффект Fill Overlay.
type: docs
url: /ru/com.aspose.slides/filloverlay/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Все реализованные интерфейсы:**
[com.aspose.slides.IFillOverlay](../../com.aspose.slides/ifilloverlay), com.aspose.slides.IVisualEffect
```
public final class FillOverlay extends ImageTransformOperation implements IFillOverlay, IVisualEffect
```

Представляет эффект Fill Overlay. Fill overlay может использоваться для указания дополнительной заливки для объекта и смешивания двух заливок вместе.
## Методы

| Метод | Описание |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Формат заливки. |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getEffective()](#getEffective--) | Получает эффективные данные эффекта Fill Overlay с применённым наследованием. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный [FillOverlay](../../com.aspose.slides/filloverlay) текущему [FillOverlay](../../com.aspose.slides/filloverlay). |
| [hashCode()](#hashCode--) | Служит в качестве хеш-функции для конкретного типа. |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Формат заливки. Только для чтения [IFillFormat](../../com.aspose.slides/ifillformat).

**Возвращает:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBlend() {#getBlend--}
```
public final int getBlend()
```

FillBlendMode. Чтение/запись [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Возвращает:**
int
### setBlend(int value) {#setBlend-int-}
```
public final void setBlend(int value)
```

FillBlendMode. Чтение/запись [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IFillOverlayEffectiveData getEffective()
```

Получает эффективные данные эффекта Fill Overlay с применённым наследованием.

**Возвращает:**
[IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata) - [IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata).
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

Определяет, равен ли указанный [FillOverlay](../../com.aspose.slides/filloverlay) текущему [FillOverlay](../../com.aspose.slides/filloverlay).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | [FillOverlay](../../com.aspose.slides/filloverlay) для сравнения. |

**Возвращает:**
boolean - true, если объекты равны; иначе false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Служит в качестве хеш-функции для конкретного типа.

**Возвращает:**
int - Хеш-код текущего объекта.