---
title: IGradientFormatEffectiveData
second_title: Aspose.Slides जावा API संदर्भ
description: एक अपरिवर्तनीय वस्तु जो प्रभावी ग्रेडिएंट भराव गुणधर्म रखती है।
type: docs
url: /hi/com.aspose.slides/igradientformateffectivedata/
---
**सभी लागू किए गए इंटरफ़ेस:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IGradientFormatEffectiveData extends IFillParamSource
```

एक अपरिवर्तनीय वस्तु जो प्रभावी ग्रेडिएंट भराव गुणधर्म रखती है।

--------------------

यह इंटरफ़ेस [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) और [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata) का हिस्सा के रूप में उपयोग किया जाता है।
## विधियाँ

| विधि | विवरण |
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


Returns the flipping mode for a gradient. केवल-पढ़ने योग्य [TileFlip](../../com.aspose.slides/tileflip)।

**वापसी:**
int
### getGradientDirection() {#getGradientDirection--}
```
public abstract int getGradientDirection()
```


Returns the style of a gradient. केवल-पढ़ने योग्य [GradientDirection](../../com.aspose.slides/gradientdirection)।

**वापसी:**
int
### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public abstract float getLinearGradientAngle()
```


Returns the angle of a gradient. केवल-पढ़ने योग्य float।

**वापसी:**
float
### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public abstract boolean getLinearGradientScaled()
```


Determines whether a gradient is scaled. केवल-पढ़ने योग्य boolean।

**वापसी:**
boolean
### getGradientShape() {#getGradientShape--}
```
public abstract byte getGradientShape()
```


Returns the shape of a gradient. केवल-पढ़ने योग्य [GradientShape](../../com.aspose.slides/gradientshape)।

**वापसी:**
byte
### getGradientStops() {#getGradientStops--}
```
public abstract IGradientStopCollectionEffectiveData getGradientStops()
```


Returns the collection of gradient stops. केवल-पढ़ने योग्य [IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)।

**वापसी:**
[IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)