---
title: IReflectionEffectiveData
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक अपरिवर्तनीय वस्तु जो परावर्तन प्रभाव का प्रतिनिधित्व करती है।
type: docs
url: /hi/com.aspose.slides/ireflectioneffectivedata/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IReflectionEffectiveData extends IEffectEffectiveData
```

एक अपरिवर्तनीय वस्तु जो परावर्तन प्रभाव का प्रतिनिधित्व करती है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getStartPosAlpha()](#getStartPosAlpha--) | प्रारम्भिक अल्फा मान (प्रतिशत) के अल्फा ग्रेडिएंट रैंप के साथ प्रारम्भिक स्थिति को निर्दिष्ट करता है। |
| [getEndPosAlpha()](#getEndPosAlpha--) | अंतिम अल्फा मान (प्रतिशत) के अल्फा ग्रेडिएंट रैंप के साथ अंतिम स्थिति को निर्दिष्ट करता है। |
| [getFadeDirection()](#getFadeDirection--) | परावर्तन को ऑफ़सेट करने की दिशा को निर्दिष्ट करता है। |
| [getStartReflectionOpacity()](#getStartReflectionOpacity--) | प्रारम्भिक परावर्तन अपैक्तता। |
| [getEndReflectionOpacity()](#getEndReflectionOpacity--) | अंतिम परावर्तन अपैक्तता। |
| [getBlurRadius()](#getBlurRadius--) | ब्लर त्रिज्या। |
| [getDirection()](#getDirection--) | परावर्तन की दिशा। |
| [getDistance()](#getDistance--) | परावर्तन की दूरी। |
| [getRectangleAlign()](#getRectangleAlign--) | आयत संरेखण। |
| [getSkewHorizontal()](#getSkewHorizontal--) | क्षैतिज स्क्यू कोण को निर्दिष्ट करता है। |
| [getSkewVertical()](#getSkewVertical--) | लंबवत स्क्यू कोण को निर्दिष्ट करता है। |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | यदि आकार घुमाया गया हो तो परावर्तन को आकार के साथ घुमाना चाहिए या नहीं, इसे निर्दिष्ट करता है। |
| [getScaleHorizontal()](#getScaleHorizontal--) | क्षैतिज स्केलिंग कारक को निर्दिष्ट करता है, नकारात्मक स्केलिंग एक फ्लिप का कारण बनती है। |
| [getScaleVertical()](#getScaleVertical--) | लंबवत स्केलिंग कारक को निर्दिष्ट करता है, नकारात्मक स्केलिंग एक फ्लिप का कारण बनती है। |
### getStartPosAlpha() {#getStartPosAlpha--}
```
public abstract float getStartPosAlpha()
```

प्रारम्भिक अल्फा मान (प्रतिशत) के अल्फा ग्रेडिएंट रैंप के साथ प्रारम्भिक स्थिति को निर्दिष्ट करता है। केवल-पढ़ने-योग्य float।

**रिटर्न:**
float
### getEndPosAlpha() {#getEndPosAlpha--}
```
public abstract float getEndPosAlpha()
```

अंतिम अल्फा मान (प्रतिशत) के अल्फा ग्रेडिएंट रैंप के साथ अंतिम स्थिति को निर्दिष्ट करता है। केवल-पढ़ने-योग्य float।

**रिटर्न:**
float
### getFadeDirection() {#getFadeDirection--}
```
public abstract float getFadeDirection()
```

परावर्तन को ऑफ़सेट करने की दिशा को निर्दिष्ट करता है (कोण)। केवल-पढ़ने-योग्य float।

**रिटर्न:**
float
### getStartReflectionOpacity() {#getStartReflectionOpacity--}
```
public abstract float getStartReflectionOpacity()
```

प्रारम्भिक परावर्तन अपैक्तता (प्रतिशत)। केवल-पढ़ने-योग्य float।

**रिटर्न:**
float
### getEndReflectionOpacity() {#getEndReflectionOpacity--}
```
public abstract float getEndReflectionOpacity()
```

अंतिम परावर्तन अपैक्तता (प्रतिशत)। केवल-पढ़ने-योग्य float।

**रिटर्न:**
float
### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

ब्लर त्रिज्या। केवल-पढ़ने-योग्य double।

**रिटर्न:**
double
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

परावर्तन की दिशा। केवल-पढ़ने-योग्य float।

**रिटर्न:**
float
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

परावर्तन की दूरी। केवल-पढ़ने-योग्य double।

**रिटर्न:**
double
### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

आयत संरेखण। केवल-पढ़ने-योग्य [RectangleAlignment](../../com.aspose.slides/rectanglealignment)।

**रिटर्न:**
byte
### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

क्षैतिज स्क्यू कोण को निर्दिष्ट करता है। केवल-पढ़ने-योग्य double।

**रिटर्न:**
double
### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

लंबवत स्क्यू कोण को निर्दिष्ट करता है। केवल-पढ़ने-योग्य double।

**रिटर्न:**
double
### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

यदि आकार घुमाया गया हो तो परावर्तन को आकार के साथ घुमाना चाहिए या नहीं, इसे निर्दिष्ट करता है। केवल-पढ़ने-योग्य boolean।

**रिटर्न:**
boolean
### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

क्षैतिज स्केलिंग कारक को निर्दिष्ट करता है, नकारात्मक स्केलिंग एक फ्लिप का कारण बनती है (प्रतिशत)। केवल-पढ़ने-योग्य double।

**रिटर्न:**
double
### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

लंबवत स्केलिंग कारक को निर्दिष्ट करता है, नकारात्मक स्केलिंग एक फ्लिप का कारण बनती है (प्रतिशत)। केवल-पढ़ने-योग्य double।

**रिटर्न:**
double