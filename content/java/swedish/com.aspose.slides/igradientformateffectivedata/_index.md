---
title: IGradientFormatEffectiveData
second_title: Aspose.Slides för Java API-referens
description: Oföränderligt objekt som innehåller effektiva gradientfyllningsegenskaper.
type: docs
url: /sv/com.aspose.slides/igradientformateffectivedata/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IGradientFormatEffectiveData extends IFillParamSource
```

Oföränderligt objekt som innehåller effektiva gradientfyllningsegenskaper.

--------------------

Detta gränssnitt används som en del av [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) och [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getTileFlip()](#getTileFlip--) | Returnerar vändningsläget för en gradient. |
| [getGradientDirection()](#getGradientDirection--) | Returnerar stilen för en gradient. |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | Returnerar vinkeln på en gradient. |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | Avgör om en gradient är skalad. |
| [getGradientShape()](#getGradientShape--) | Returnerar formen på en gradient. |
| [getGradientStops()](#getGradientStops--) | Returnerar samlingen av gradientstopp. |
### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```

Returnerar vändningsläget för en gradient. Skrivskyddad [TileFlip](../../com.aspose.slides/tileflip).

**Returnerar:**
int
### getGradientDirection() {#getGradientDirection--}
```
public abstract int getGradientDirection()
```

Returnerar stilen för en gradient. Skrivskyddad [GradientDirection](../../com.aspose.slides/gradientdirection).

**Returnerar:**
int
### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public abstract float getLinearGradientAngle()
```

Returnerar vinkeln på en gradient. Skrivskyddad float.

**Returnerar:**
float
### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public abstract boolean getLinearGradientScaled()
```

Avgör om en gradient är skalad. Skrivskyddad boolean.

**Returnerar:**
boolean
### getGradientShape() {#getGradientShape--}
```
public abstract byte getGradientShape()
```

Returnerar formen på en gradient. Skrivskyddad [GradientShape](../../com.aspose.slides/gradientshape).

**Returnerar:**
byte
### getGradientStops() {#getGradientStops--}
```
public abstract IGradientStopCollectionEffectiveData getGradientStops()
```

Returnerar samlingen av gradientstopp. Skrivskyddad [IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata).

**Returnerar:**
[IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)