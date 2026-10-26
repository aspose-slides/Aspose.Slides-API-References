---
title: IGradientFormatEffectiveData
second_title: Aspose.Slides för Android via Java API-referens
description: Immutabelt objekt som innehåller effektiva gradientfyllningsegenskaper.
type: docs
url: /sv/com.aspose.slides/igradientformateffectivedata/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IGradientFormatEffectiveData extends IFillParamSource
```

Imutable-objekt som innehåller effektiva gradientfyllningsegenskaper.

--------------------

Detta gränssnitt används som en del av [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) och [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getTileFlip()](#getTileFlip--) | Returnerar flippningsläget för en gradient. |
| [getGradientDirection()](#getGradientDirection--) | Returnerar stilen för en gradient. |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | Returnerar vinkeln för en gradient. |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | Avgör om en gradient är skalad. |
| [getGradientShape()](#getGradientShape--) | Returnerar formen för en gradient. |
| [getGradientStops()](#getGradientStops--) | Returnerar samlingen av gradientstopp. |
### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```


Returnerar flippningsläget för en gradient. Endast läsning [TileFlip](../../com.aspose.slides/tileflip).

**Returnerar:**
int
### getGradientDirection() {#getGradientDirection--}
```
public abstract int getGradientDirection()
```


Returnerar stilen för en gradient. Endast läsning [GradientDirection](../../com.aspose.slides/gradientdirection).

**Returnerar:**
int
### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public abstract float getLinearGradientAngle()
```


Returnerar vinkeln för en gradient. Endast läsning float.

**Returnerar:**
float
### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public abstract boolean getLinearGradientScaled()
```


Avgör om en gradient är skalad. Endast läsning boolean.

**Returnerar:**
boolean
### getGradientShape() {#getGradientShape--}
```
public abstract byte getGradientShape()
```


Returnerar formen för en gradient. Endast läsning [GradientShape](../../com.aspose.slides/gradientshape).

**Returnerar:**
byte
### getGradientStops() {#getGradientStops--}
```
public abstract IGradientStopCollectionEffectiveData getGradientStops()
```


Returnerar samlingen av gradientstopp. Endast läsning [IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata).

**Returnerar:**
[IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)