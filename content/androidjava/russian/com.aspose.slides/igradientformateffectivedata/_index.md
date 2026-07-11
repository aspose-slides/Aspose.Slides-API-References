---
title: IGradientFormatEffectiveData
second_title: Aspose.Slides для Android через справочник Java API
description: Неизменяемый объект, содержащий эффективные свойства градиентного заполнения.
type: docs
url: /ru/com.aspose.slides/igradientformateffectivedata/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IGradientFormatEffectiveData extends IFillParamSource
```

Неизменяемый объект, содержащий эффективные свойства градиентного заполнения.

--------------------

Этот интерфейс используется как часть [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) и [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## Методы

| Метод | Описание |
| --- | --- |
| [getTileFlip()](#getTileFlip--) | Возвращает режим отражения для градиента. |
| [getGradientDirection()](#getGradientDirection--) | Возвращает стиль градиента. |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | Возвращает угол градиента. |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | Определяет, масштабируется ли градиент. |
| [getGradientShape()](#getGradientShape--) | Возвращает форму градиента. |
| [getGradientStops()](#getGradientStops--) | Возвращает коллекцию точек градиента. |
### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```

Возвращает режим отражения для градиента. Только для чтения [TileFlip](../../com.aspose.slides/tileflip).

**Возвращает:**  
int
### getGradientDirection() {#getGradientDirection--}
```
public abstract int getGradientDirection()
```

Возвращает стиль градиента. Только для чтения [GradientDirection](../../com.aspose.slides/gradientdirection).

**Возвращает:**  
int
### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public abstract float getLinearGradientAngle()
```

Возвращает угол градиента. Только для чтения float.

**Возвращает:**  
float
### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public abstract boolean getLinearGradientScaled()
```

Определяет, масштабируется ли градиент. Только для чтения boolean.

**Возвращает:**  
boolean
### getGradientShape() {#getGradientShape--}
```
public abstract byte getGradientShape()
```

Возвращает форму градиента. Только для чтения [GradientShape](../../com.aspose.slides/gradientshape).

**Возвращает:**  
byte
### getGradientStops() {#getGradientStops--}
```
public abstract IGradientStopCollectionEffectiveData getGradientStops()
```

Возвращает коллекцию точек градиента. Только для чтения [IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata).

**Возвращает:**  
[IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)