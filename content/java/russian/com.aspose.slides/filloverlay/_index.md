---
title: FillOverlay
second_title: Справочник API Aspose.Slides для Java
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

Представляет эффект Fill Overlay. Fill Overlay может использоваться для указания дополнительной заливки объекта и смешения двух заливок вместе.
## Методы

| Метод | Описание |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Формат заливки. |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getEffective()](#getEffective--) | Получает эффективные данные эффекта Fill Overlay с применённым наследованием. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный [FillOverlay](../../com.aspose.slides/filloverlay) текущему [FillOverlay](../../com.aspose.slides/filloverlay). |
| [hashCode()](#hashCode--) | Служит хеш-функцией для конкретного типа. |
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IFillOverlayEffectiveData getEffective()
```


Получает эффективные данные эффекта Fill Overlay с учётом наследования.

**Возвращает:**
[IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata) - A [IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata).
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
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The [FillOverlay](../../com.aspose.slides/filloverlay) to compare. |

**Возвращает:**
boolean - true, если объекты равны; иначе false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Служит хеш-функцией для конкретного типа.

**Возвращает:**
int - Хеш-код текущего объекта.