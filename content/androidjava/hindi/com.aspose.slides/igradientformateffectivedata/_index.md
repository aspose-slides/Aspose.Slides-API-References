---
title: IGradientFormatEffectiveData
second_title: Aspose.Slides for Android के लिए जावा API संदर्भ
description: एक अपरिवर्तनीय वस्तु जो प्रभावी ग्रेडिएंट भरने गुणधर्मों को समाहित करती है।
type: docs
url: /hi/com.aspose.slides/igradientformateffectivedata/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IGradientFormatEffectiveData extends IFillParamSource
```

एक अपरिवर्तनीय ऑब्जेक्ट जो प्रभावी ग्रेडिएंट भरने गुणधर्मों को समाहित करता है।

--------------------

यह इंटरफ़ेस [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) और [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata) का एक भाग के रूप में उपयोग किया जाता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getTileFlip()](#getTileFlip--) | एक ग्रेडिएंट के लिए फ्लिपिंग मोड लौटाता है। |
| [getGradientDirection()](#getGradientDirection--) | एक ग्रेडिएंट की शैली लौटाता है। |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | एक ग्रेडिएंट का कोण लौटाता है। |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | निर्धारित करता है कि ग्रेडिएंट स्केल किया गया है या नहीं। |
| [getGradientShape()](#getGradientShape--) | एक ग्रेडिएंट का आकार लौटाता है। |
| [getGradientStops()](#getGradientStops--) | ग्रेडिएंट स्टॉप्स का संग्रह लौटाता है। |
### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```

एक ग्रेडिएंट के लिए फ्लिपिंग मोड लौटाता है। केवल पढ़ने योग्य [TileFlip](../../com.aspose.slides/tileflip)।

**रिटर्न:**  
int
### getGradientDirection() {#getGradientDirection--}
```
public abstract int getGradientDirection()
```

एक ग्रेडिएंट की शैली लौटाता है। केवल पढ़ने योग्य [GradientDirection](../../com.aspose.slides/gradientdirection)।

**रिटर्न:**  
int
### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public abstract float getLinearGradientAngle()
```

एक ग्रेडिएंट का कोण लौटाता है। केवल पढ़ने योग्य float।

**रिटर्न:**  
float
### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public abstract boolean getLinearGradientScaled()
```

निर्धारित करता है कि ग्रेडिएंट स्केल किया गया है या नहीं। केवल पढ़ने योग्य boolean।

**रिटर्न:**  
boolean
### getGradientShape() {#getGradientShape--}
```
public abstract byte getGradientShape()
```

एक ग्रेडिएंट का आकार लौटाता है। केवल पढ़ने योग्य [GradientShape](../../com.aspose.slides/gradientshape)।

**रिटर्न:**  
byte
### getGradientStops() {#getGradientStops--}
```
public abstract IGradientStopCollectionEffectiveData getGradientStops()
```

ग्रेडिएंट स्टॉप्स का संग्रह लौटाता है। केवल पढ़ने योग्य [IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)।

**रिटर्न:**  
[IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)