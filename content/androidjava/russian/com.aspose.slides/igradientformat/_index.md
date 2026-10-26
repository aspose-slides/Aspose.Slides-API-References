---
title: IGradientFormat
second_title: Aspose.Slides для Android через Java API Reference
description: Представляет формат градиента.
type: docs
url: /ru/com.aspose.slides/igradientformat/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IGradientFormat extends IFillParamSource
```

Представляет формат градиента.
## Методы

| Метод | Описание |
| --- | --- |
| [getTileFlip()](#getTileFlip--) | Возвращает или задает режим отражения для градиента. |
| [setTileFlip(int value)](#setTileFlip-int-) | Возвращает или задает режим отражения для градиента. |
| [getGradientDirection()](#getGradientDirection--) | Возвращает или задает стиль градиента. |
| [setGradientDirection(int value)](#setGradientDirection-int-) | Возвращает или задает стиль градиента. |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | Возвращает или задает угол градиента. |
| [setLinearGradientAngle(float value)](#setLinearGradientAngle-float-) | Возвращает или задает угол градиента. |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | Определяет, масштабируется ли градиент. |
| [setLinearGradientScaled(byte value)](#setLinearGradientScaled-byte-) | Определяет, масштабируется ли градиент. |
| [getGradientShape()](#getGradientShape--) | Возвращает или задает форму градиента. |
| [setGradientShape(byte value)](#setGradientShape-byte-) | Возвращает или задает форму градиента. |
| [getGradientStops()](#getGradientStops--) | Возвращает коллекцию остановок градиента. |
### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```

Возвращает или задает режим отражения для градиента. Чтение/запись [TileFlip](../../com.aspose.slides/tileflip).

**Возвращает:**
int
### setTileFlip(int value) {#setTileFlip-int-}
```
public abstract void setTileFlip(int value)
```

Возвращает или задает режим отражения для градиента. Чтение/запись [TileFlip](../../com.aspose.slides/tileflip).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getGradientDirection() {#getGradientDirection--}
```
public abstract int getGradientDirection()
```

Возвращает или задает стиль градиента. Чтение/запись [GradientDirection](../../com.aspose.slides/gradientdirection).

**Возвращает:**
int
### setGradientDirection(int value) {#setGradientDirection-int-}
```
public abstract void setGradientDirection(int value)
```

Возвращает или задает стиль градиента. Чтение/запись [GradientDirection](../../com.aspose.slides/gradientdirection).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public abstract float getLinearGradientAngle()
```

Возвращает или задает угол градиента. Чтение/запись float.

**Возвращает:**
float
### setLinearGradientAngle(float value) {#setLinearGradientAngle-float-}
```
public abstract void setLinearGradientAngle(float value)
```

Возвращает или задает угол градиента. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |
### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public abstract byte getLinearGradientScaled()
```

Определяет, масштабируется ли градиент. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращает:**
byte
### setLinearGradientScaled(byte value) {#setLinearGradientScaled-byte-}
```
public abstract void setLinearGradientScaled(byte value)
```

Определяет, масштабируется ли градиент. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getGradientShape() {#getGradientShape--}
```
public abstract byte getGradientShape()
```

Возвращает или задает форму градиента. Чтение/запись [GradientShape](../../com.aspose.slides/gradientshape).

**Возвращает:**
byte
### setGradientShape(byte value) {#setGradientShape-byte-}
```
public abstract void setGradientShape(byte value)
```

Возвращает или задает форму градиента. Чтение/запись [GradientShape](../../com.aspose.slides/gradientshape).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getGradientStops() {#getGradientStops--}
```
public abstract IGradientStopCollection getGradientStops()
```

Возвращает коллекцию остановок градиента. Только для чтения [IGradientStopCollection](../../com.aspose.slides/igradientstopcollection).

**Возвращает:**
[IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)