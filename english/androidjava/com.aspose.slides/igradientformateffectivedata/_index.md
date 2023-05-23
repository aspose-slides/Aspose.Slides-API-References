---
title: IGradientFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Imutable object which contains effective gradient filling properties.
type: docs
weight: 810
url: /androidjava/com.aspose.slides/igradientformateffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IGradientFormatEffectiveData extends IFillParamSource
```

Imutable object which contains effective gradient filling properties.

--------------------

This interface is used as a part of [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) and [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## Methods

| Method | Description |
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


Returns the flipping mode for a gradient. Read-only [TileFlip](../../com.aspose.slides/tileflip).

**Returns:**
int
### getGradientDirection() {#getGradientDirection--}
```
public abstract int getGradientDirection()
```


Returns the style of a gradient. Read-only [GradientDirection](../../com.aspose.slides/gradientdirection).

**Returns:**
int
### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public abstract float getLinearGradientAngle()
```


Returns the angle of a gradient. Read-only float.

**Returns:**
float
### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public abstract boolean getLinearGradientScaled()
```


Determines whether a gradient is scaled. Read-only boolean.

**Returns:**
boolean
### getGradientShape() {#getGradientShape--}
```
public abstract byte getGradientShape()
```


Returns the shape of a gradient. Read-only [GradientShape](../../com.aspose.slides/gradientshape).

**Returns:**
byte
### getGradientStops() {#getGradientStops--}
```
public abstract IGradientStopCollectionEffectiveData getGradientStops()
```


Returns the collection of gradient stops. Read-only [IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata).

**Returns:**
[IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)
