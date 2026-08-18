---
title: IGradientFormatEffectiveData
second_title: Aspose.Slides dla Java – odniesienie API
description: Niezmienny obiekt zawierający efektywne właściwości wypełniania gradientem.
type: docs
url: /pl/com.aspose.slides/igradientformateffectivedata/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IGradientFormatEffectiveData extends IFillParamSource
```

Niezmienny obiekt zawierający efektywne właściwości wypełniania gradientem.

--------------------

Ten interfejs jest używany jako część [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) i [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## Metody

| Metoda | Opis |
| --- | --- |
| [getTileFlip()](#getTileFlip--) | Returns the flipping mode for a gradient. |
| [getGradientDirection()](#getGradientDirection--) | Returns the style of a gradient. |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | Returns the angle of a gradient. |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | Determines whether a gradient is scaled. |
| [getGradientShape()](#getGradientShape--) | Returns the shape of a gradient. |
| [getGradientStops()](#getGradientStops--) | Returns the collection of gradient stops. |
### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```


Zwraca tryb odbicia gradientu. Tylko do odczytu [TileFlip](../../com.aspose.slides/tileflip).

**Zwraca:**
int
### getGradientDirection() {#getGradientDirection--}
```
public abstract int getGradientDirection()
```


Zwraca styl gradientu. Tylko do odczytu [GradientDirection](../../com.aspose.slides/gradientdirection).

**Zwraca:**
int
### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public abstract float getLinearGradientAngle()
```


Zwraca kąt gradientu. Tylko do odczytu float.

**Zwraca:**
float
### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public abstract boolean getLinearGradientScaled()
```


Określa, czy gradient jest skalowany. Tylko do odczytu boolean.

**Zwraca:**
boolean
### getGradientShape() {#getGradientShape--}
```
public abstract byte getGradientShape()
```


Zwraca kształt gradientu. Tylko do odczytu [GradientShape](../../com.aspose.slides/gradientshape).

**Zwraca:**
byte
### getGradientStops() {#getGradientStops--}
```
public abstract IGradientStopCollectionEffectiveData getGradientStops()
```


Zwraca kolekcję punktów gradientu. Tylko do odczytu [IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata).

**Zwraca:**
[IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)