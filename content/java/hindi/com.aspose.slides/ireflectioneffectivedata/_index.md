---
title: IReflectionEffectiveData
second_title: Aspose.Slides for Java API संदर्भ
description: अपरिवर्तनीय वस्तु जो एक प्रतिबिंब प्रभाव का प्रतिनिधित्व करती है।
type: docs
url: /hi/com.aspose.slides/ireflectioneffectivedata/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IReflectionEffectiveData extends IEffectEffectiveData
```

एक अपरिवर्तनीय वस्तु जो एक प्रतिबिंब प्रभाव का प्रतिनिधित्व करती है।
## विधियां

| विधि | विवरण |
| --- | --- |
| [getStartPosAlpha()](#getStartPosAlpha--) | शूरुआती अल्फा मान (प्रतिशत) की प्रारंभिक स्थिति (अल्फा ग्रेडिएंट रैंप के साथ) निर्दिष्ट करता है। |
| [getEndPosAlpha()](#getEndPosAlpha--) | अंतिम अल्फा मान (प्रतिशत) की समाप्ति स्थिति (अल्फा ग्रेडिएंट रैंप के साथ) निर्दिष्ट करता है। |
| [getFadeDirection()](#getFadeDirection--) | परावर्तन को ऑफ़सेट करने की दिशा निर्दिष्ट करता है। |
| [getStartReflectionOpacity()](#getStartReflectionOpacity--) | प्रारंभिक परावर्तन अपारदर्शिता। (प्रतिशत) |
| [getEndReflectionOpacity()](#getEndReflectionOpacity--) | अंतिम परावर्तन अपारदर्शिता। (प्रतिशत) |
| [getBlurRadius()](#getBlurRadius--) | ब्लर त्रिज्या। |
| [getDirection()](#getDirection--) | परावर्तन की दिशा। |
| [getDistance()](#getDistance--) | परावर्तन की दूरी। |
| [getRectangleAlign()](#getRectangleAlign--) | आयत संरेखण। |
| [getSkewHorizontal()](#getSkewHorizontal--) | क्षैतिज स्क्यू कोण निर्दिष्ट करता है। |
| [getSkewVertical()](#getSkewVertical--) | ऊर्ध्वाधर स्क्यू कोण निर्दिष्ट करता है। |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | यदि आकार घुमा दिया गया है तो परावर्तन को आकार के साथ घुमाया जाना चाहिए या नहीं, यह निर्दिष्ट करता है। |
| [getScaleHorizontal()](#getScaleHorizontal--) | क्षैतिज स्केलिंग फैक्टर निर्दिष्ट करता है, नकारात्मक स्केलिंग फ़्लिप का कारण बनता है। |
| [getScaleVertical()](#getScaleVertical--) | ऊर्ध्वाधर स्केलिंग फैक्टर निर्दिष्ट करता है, नकारात्मक स्केलिंग फ़्लिप का कारण बनता है। |
### getStartPosAlpha() {#getStartPosAlpha--}
```
public abstract float getStartPosAlpha()
```


शुरुआती अल्फा मान (प्रतिशत) की प्रारंभिक स्थिति (अल्फा ग्रेडिएंट रैंप के साथ) निर्दिष्ट करता है। केवल पढ़ने योग्य float।

**वापसी:**
float
### getEndPosAlpha() {#getEndPosAlpha--}
```
public abstract float getEndPosAlpha()
```


अंतिम अल्फा मान (प्रतिशत) की समाप्ति स्थिति (अल्फा ग्रेडिएंट रैंप के साथ) निर्दिष्ट करता है। केवल पढ़ने योग्य float।

**वापसी:**
float
### getFadeDirection() {#getFadeDirection--}
```
public abstract float getFadeDirection()
```


परावर्तन को ऑफ़सेट करने की दिशा निर्दिष्ट करता है। (कोण)। केवल पढ़ने योग्य float।

**वापसी:**
float
### getStartReflectionOpacity() {#getStartReflectionOpacity--}
```
public abstract float getStartReflectionOpacity()
```


प्रारंभिक परावर्तन अपारदर्शिता। (प्रतिशत)। केवल पढ़ने योग्य float।

**वापसी:**
float
### getEndReflectionOpacity() {#getEndReflectionOpacity--}
```
public abstract float getEndReflectionOpacity()
```


अंतिम परावर्तन अपारदर्शिता। (प्रतिशत)। केवल पढ़ने योग्य float।

**वापसी:**
float
### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```


ब्लर त्रिज्या। केवल पढ़ने योग्य double।

**वापसी:**
double
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```


परावर्तन की दिशा। केवल पढ़ने योग्य float।

**वापसी:**
float
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```


परावर्तन की दूरी। केवल पढ़ने योग्य double।

**वापसी:**
double
### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```


आयत संरेखण। केवल पढ़ने योग्य [RectangleAlignment](../../com.aspose.slides/rectanglealignment)।

**वापसी:**
byte
### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```


क्षैतिज स्क्यू कोण निर्दिष्ट करता है। केवल पढ़ने योग्य double।

**वापसी:**
double
### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```


ऊर्ध्वाधर स्क्यू कोण निर्दिष्ट करता है। केवल पढ़ने योग्य double।

**वापसी:**
double
### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```


यदि आकार घुमा दिया गया है तो परावर्तन को आकार के साथ घुमाया जाना चाहिए या नहीं, यह निर्दिष्ट करता है। केवल पढ़ने योग्य boolean।

**वापसी:**
boolean
### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```


क्षैतिज स्केलिंग फैक्टर निर्दिष्ट करता है, नकारात्मक स्केलिंग फ़्लिप का कारण बनता है। (प्रतिशत) केवल पढ़ने योग्य double।

**वापसी:**
double
### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```


ऊर्ध्वाधर स्केलिंग फैक्टर निर्दिष्ट करता है, नकारात्मक स्केलिंग फ़्लिप का कारण बनता है। (प्रतिशत) केवल पढ़ने योग्य double।

**वापसी:**
double