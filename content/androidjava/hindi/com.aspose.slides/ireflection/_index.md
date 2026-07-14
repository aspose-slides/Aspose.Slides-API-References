---
title: IReflection
second_title: Aspose.Slides Android के लिए, Java API रेफ़रेंस के माध्यम से
description: एक परावर्तन प्रभाव का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ireflection/
---
**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject  
```
public interface IReflection extends IImageTransformOperation, IAccessiblePVIObject<IReflectionEffectiveData>
```

परावर्तन प्रभाव को दर्शाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getStartPosAlpha()](#getStartPosAlpha--) | स्टार्ट अल्फा मान (प्रतिशत) की प्रारंभिक स्थिति (अल्फा ग्रेडिएंट रैंप के साथ) को निर्दिष्ट करता है। |
| [setStartPosAlpha(float value)](#setStartPosAlpha-float-) | स्टार्ट अल्फा मान (प्रतिशत) की प्रारंभिक स्थिति (अल्फा ग्रेडिएंट रैंप के साथ) को निर्दिष्ट करता है। |
| [getEndPosAlpha()](#getEndPosAlpha--) | एंड अल्फा मान (प्रतिशत) की अंतिम स्थिति (अल्फा ग्रेडिएंट रैंप के साथ) को निर्दिष्ट करता है। |
| [setEndPosAlpha(float value)](#setEndPosAlpha-float-) | एंड अल्फा मान (प्रतिशत) की अंतिम स्थिति (अल्फा ग्रेडिएंट रैंप के साथ) को निर्दिष्ट करता है। |
| [getFadeDirection()](#getFadeDirection--) | परावर्तन को ऑफ़सेट करने की दिशा निर्दिष्ट करता है। |
| [setFadeDirection(float value)](#setFadeDirection-float-) | परावर्तन को ऑफ़सेट करने की दिशा निर्दिष्ट करता है। |
| [getStartReflectionOpacity()](#getStartReflectionOpacity--) | परावर्तन की प्रारंभिक अस्पष्टता। |
| [setStartReflectionOpacity(float value)](#setStartReflectionOpacity-float-) | परावर्तन की प्रारंभिक अस्पृष्टता। |
| [getEndReflectionOpacity()](#getEndReflectionOpacity--) | परावर्तन की अंतिम अस्पृष्टता। |
| [setEndReflectionOpacity(float value)](#setEndReflectionOpacity-float-) | परावर्तन की अंतिम अस्पृष्टता। |
| [getBlurRadius()](#getBlurRadius--) | ब्लर त्रिज्या। |
| [setBlurRadius(double value)](#setBlurRadius-double-) | ब्लर त्रिज्या। |
| [getDirection()](#getDirection--) | परावर्तन की दिशा। |
| [setDirection(float value)](#setDirection-float-) | परावर्तन की दिशा। |
| [getDistance()](#getDistance--) | परावर्तन की दूरी। |
| [setDistance(double value)](#setDistance-double-) | परावर्तन की दूरी। |
| [getRectangleAlign()](#getRectangleAlign--) | आयत संरेखण। |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | आयत संरेखण। |
| [getSkewHorizontal()](#getSkewHorizontal--) | क्षैतिज स्क्यू कोण को निर्दिष्ट करता है। |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | क्षैतिज स्क्यू कोण को निर्दिष्ट करता है। |
| [getSkewVertical()](#getSkewVertical--) | ऊभ्र स्क्यू कोण को निर्दिष्ट करता है। |
| [setSkewVertical(double value)](#setSkewVertical-double-) | ऊभ्र स्क्यू कोण को निर्दिष्ट करता है। |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | यदि आकार घुमाया गया हो तो परावर्तन को आकार के साथ घुमाया जाना चाहिए या नहीं, इसे निर्दिष्ट करता है। |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | यदि आकार घुमाया गया हो तो परावर्तन को आकार के साथ घुमाया जाना चाहिए या नहीं, इसे निर्दिष्ट करता है। |
| [getScaleHorizontal()](#getScaleHorizontal--) | क्षैतिज स्केलिंग फैक्टर को निर्दिष्ट करता है, नकारात्मक स्केलिंग उलटना कारण बनता है। (प्रतिशत) |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | क्षैतिज स्केलिंग फैक्टर को निर्दिष्ट करता है, नकारात्मक स्केलिंग उलटना कारण बनता है। (प्रतिशत) |
| [getScaleVertical()](#getScaleVertical--) | ऊभ्र स्केलिंग फैक्टर को निर्दिष्ट करता है, नकारात्मक स्केलिंग उलटना कारण बनता है। (प्रतिशत) |
| [setScaleVertical(double value)](#setScaleVertical-double-) | ऊभ्र स्केलिंग फैक्टर को निर्दिष्ट करता है, नकारात्मक स्केलिंग उलटना कारण बनता है। (प्रतिशत) |

### getStartPosAlpha() {#getStartPosAlpha--}
```
public abstract float getStartPosAlpha()
```

स्टार्ट अल्फा मान (प्रतिशत) की प्रारंभिक स्थिति (अल्फा ग्रेडिएंट रैंप के साथ) को निर्दिष्ट करता है। पढ़ने/लिखने योग्य float।

**वापसी:**
float

### setStartPosAlpha(float value) {#setStartPosAlpha-float-}
```
public abstract void setStartPosAlpha(float value)
```

स्टार्ट अल्फा मान (प्रतिशत) की प्रारंभिक स्थिति (अल्फा ग्रेडिएंट रैंप के साथ) को निर्दिष्ट करता है। पढ़ने/लिखने योग्य float।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getEndPosAlpha() {#getEndPosAlpha--}
```
public abstract float getEndPosAlpha()
```

एंड अल्फा मान (प्रतिशत) की अंतिम स्थिति (अल्फा ग्रेडिएंट रैंप के साथ) को निर्दिष्ट करता है। पढ़ने/लिखने योग्य float।

**वापसी:**
float

### setEndPosAlpha(float value) {#setEndPosAlpha-float-}
```
public abstract void setEndPosAlpha(float value)
```

एंड अल्फा मान (प्रतिशत) की अंतिम स्थिति (अल्फा ग्रेडिएंट रैंप के साथ) को निर्दिष्ट करता है। पढ़ने/लिखने योग्य float।

**परامیटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getFadeDirection() {#getFadeDirection--}
```
public abstract float getFadeDirection()
```

परावर्तन को ऑफ़सेट करने की दिशा निर्दिष्ट करता है। (कोण) पढ़ने/लिखने योग्य float।

**वापसी:**
float

### setFadeDirection(float value) {#setFadeDirection-float-}
```
public abstract void setFadeDirection(float value)
```

परावर्तन को ऑफ़सेट करने की दिशा निर्दिष्ट करता है। (कोण) पढ़ने/लिखने योग्य float।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getStartReflectionOpacity() {#getStartReflectionOpacity--}
```
public abstract float getStartReflectionOpacity()
```

परावर्तन की प्रारंभिक अस्पृष्टता। (प्रतिशत) पढ़ने/लिखने योग्य float।

**वापसी:**
float

### setStartReflectionOpacity(float value) {#setStartReflectionOpacity-float-}
```
public abstract void setStartReflectionOpacity(float value)
```

परावर्तन की प्रारंभिक अस्पृष्टता। (प्रतिशत) पढ़ने/लिखने योग्य float।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getEndReflectionOpacity() {#getEndReflectionOpacity--}
```
public abstract float getEndReflectionOpacity()
```

परावर्तन की अंतिम अस्पृष्टता। (प्रतिशत) पढ़ने/लिखने योग्य float।

**वापसी:**
float

### setEndReflectionOpacity(float value) {#setEndReflectionOpacity-float-}
```
public abstract void setEndReflectionOpacity(float value)
```

परावर्तन की अंतिम अस्पृष्टता। (प्रतिशत) पढ़ने/लिखने योग्य float।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

ब्लर त्रिज्या। पढ़ने/लिखने योग्य double।

**वापसी:**
double

### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```

ब्लर त्रिज्या। पढ़ने/लिखने योग्य double।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

परावर्तन की दिशा। पढ़ने/लिखने योग्य float।

**वापसी:**
float

### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

परावर्तन की दिशा। पढ़ने/लिखने योग्य float।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

परावर्तन की दूरी। पढ़ने/लिखने योग्य double।

**वापसी:**
double

### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

परावर्तन की दूरी। पढ़ने/लिखने योग्य double।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

आयत संरेखण। पढ़ने/लिखने योग्य [RectangleAlignment](../../com.aspose.slides/rectanglealignment)।

**वापसी:**
byte

### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public abstract void setRectangleAlign(byte value)
```

आयत संरेखण। पढ़ने/लिखने योग्य [RectangleAlignment](../../com.aspose.slides/rectanglealignment)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

क्षैतिज स्क्यू कोण को निर्दिष्ट करता है। पढ़ने/लिखने योग्य double।

**वापसी:**
double

### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public abstract void setSkewHorizontal(double value)
```

क्षैतिज स्क्यू कोण को निर्दिष्ट करता है। पढ़ने/लिखने योग्य double।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

ऊभ्र स्क्यू कोण को निर्दिष्ट करता है। पढ़ने/लिखने योग्य double।

**वापसी:**
double

### setSkewVertical(double value) {#setSkewVertical-double-}
```
public abstract void setSkewVertical(double value)
```

ऊभ्र स्क्यू कोण को निर्दिष्ट करता है। पढ़ने/लिखने योग्य double।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

यदि आकार घुमाया गया हो तो परावर्तन को आकार के साथ घुमाया जाना चाहिए या नहीं, इसे निर्दिष्ट करता है। पढ़ने/लिखने योग्य boolean।

**वापसी:**
boolean

### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public abstract void setRotateShadowWithShape(boolean value)
```

यदि आकार घुमाया गया हो तो परावर्तन को आकार के साथ घुमाया जाना चाहिए या नहीं, इसे निर्दिष्ट करता है। पढ़ने/लिखने योग्य boolean।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

क्षैतिज स्केलिंग फैक्टर को निर्दिष्ट करता है, नकारात्मक स्केलिंग उलटना कारण बनता है। (प्रतिशत) पढ़ने/लिखने योग्य double।

**वापसी:**
double

### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public abstract void setScaleHorizontal(double value)
```

क्षैतिज स्केलिंग फैक्टर को निर्दिष्ट करता है, नकारात्मक स्केलिंग उलटना कारण बनता है। (प्रतिशत) पढ़ने/लिखने योग्य double।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

ऊभ्र स्केलिंग फैक्टर को निर्दिष्ट करता है, नकारात्मक स्केलिंग उलटना कारण बनता है। (प्रतिशत) पढ़ने/लिखने योग्य double।

**वापसी:**
double

### setScaleVertical(double value) {#setScaleVertical-double-}
```
public abstract void setScaleVertical(double value)
```

ऊभ्र स्केलिंग फैक्टर को निर्दिष्ट करता है, नकारात्मक स्केलिंग उलटना कारण बनता है। (प्रतिशत) पढ़ने/लिखने योग्य double।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |