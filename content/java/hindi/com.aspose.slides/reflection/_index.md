---
title: Reflection
second_title: Aspose.Slides के लिए Java API संदर्भ
description: एक Reflection प्रभाव का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/reflection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IReflection](../../com.aspose.slides/ireflection), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class Reflection implements IReflection, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

एक Reflection प्रभाव का प्रतिनिधित्व करता है।

## विधियां

| विधि | विवरण |
| --- | --- |
| [getStartPosAlpha()](#getStartPosAlpha--) | शुरू स्थिति (अल्फा ग्रेडिएंट रैंप के साथ) के शुरुआती अल्फा मान (प्रतिशत) को निर्दिष्ट करता है। |
| [setStartPosAlpha(float value)](#setStartPosAlpha-float-) | शुरू स्थिति (अल्फा ग्रेडिएंट रैंप के साथ) के शुरुआती अल्फा मान (प्रतिशत) को निर्दिष्ट करता है। |
| [getEndPosAlpha()](#getEndPosAlpha--) | अंत स्थिति (अल्फा ग्रेडिएंट रैंप के साथ) के अंत अल्फा मान (प्रतिशत) को निर्दिष्ट करता है। |
| [setEndPosAlpha(float value)](#setEndPosAlpha-float-) | अंत स्थिति (अल्फा ग्रेडिएंट रैंप के साथ) के अंत अल्फा मान (प्रतिशत) को निर्दिष्ट करता है। |
| [getFadeDirection()](#getFadeDirection--) | परावर्तन को ऑफ़सेट करने की दिशा को निर्दिष्ट करता है। |
| [setFadeDirection(float value)](#setFadeDirection-float-) | परावर्तन को ऑफ़सेट करने की दिशा को निर्दिष्ट करता है। |
| [getStartReflectionOpacity()](#getStartReflectionOpacity--) | परावर्तन की प्रारंभिक अस्पष्टता। |
| [setStartReflectionOpacity(float value)](#setStartReflectionOpacity-float-) | परावर्तन की प्रारंभिक अस्पष्टता। |
| [getEndReflectionOpacity()](#getEndReflectionOpacity--) | परावर्तन की अंतिम अस्पष्टता। |
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
| [getSkewVertical()](#getSkewVertical--) | ऊर्ध्वाधर स्क्यू कोण को निर्दिष्ट करता है। |
| [setSkewVertical(double value)](#setSkewVertical-double-) | ऊर्ध्वाधर स्क्यू कोण को निर्दिष्ट करता है। |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | यदि आकार घुमाया गया है, तो परावर्तन को आकार के साथ घुमाना चाहिए या नहीं, इसे निर्दिष्ट करता है। |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | यदि आकार घुमाया गया है, तो परावर्तन को आकार के साथ घुमाना चाहिए या नहीं, इसे निर्दिष्ट करता है। |
| [getScaleHorizontal()](#getScaleHorizontal--) | क्षैतिज स्केलिंग कारक को निर्दिष्ट करता है, नकारात्मक स्केलिंग फ्लिप का कारण बनती है। |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | क्षैतिज स्केलिंग कारक को निर्दिष्ट करता है, नकारात्मक स्केलिंग फ्लिप का कारण बनती है। |
| [getScaleVertical()](#getScaleVertical--) | ऊर्ध्वाधर स्केलिंग कारक को निर्दिष्ट करता है, नकारात्मक स्केलिंग फ्लिप का कारण बनती है। |
| [setScaleVertical(double value)](#setScaleVertical-double-) | ऊर्ध्वाधर स्केलिंग कारक को निर्दिष्ट करता है, नकारात्मक स्केलिंग फ्लिप का कारण बनती है। |
| [getEffective()](#getEffective--) | विरासत लागू होने के साथ प्रभावी Reflection प्रभाव डेटा प्राप्त करता है। |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि निर्दिष्ट [Reflection](../../com.aspose.slides/reflection) वर्तमान [Reflection](../../com.aspose.slides/reflection) के बराबर है या नहीं। |
| [hashCode()](#hashCode--) | किसी विशिष्ट प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है। |

### getStartPosAlpha() {#getStartPosAlpha--}
```
public final float getStartPosAlpha()
```

शुरुआती अल्फा मान (प्रतिशत) के अल्फा ग्रेडिएंट रैंप के साथ शुरू स्थिति को निर्दिष्ट करता है। पढ़ें/लिखें float.

**रिटर्न:**
float

### setStartPosAlpha(float value) {#setStartPosAlpha-float-}
```
public final void setStartPosAlpha(float value)
```

शुरुआती अल्फा मान (प्रतिशत) के अल्फा ग्रेडिएंट रैंप के साथ शुरू स्थिति को निर्दिष्ट करता है। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getEndPosAlpha() {#getEndPosAlpha--}
```
public final float getEndPosAlpha()
```

अंत अल्फा मान (प्रतिशत) के अल्फा ग्रेडिएंट रैंप के साथ अंत स्थिति को निर्दिष्ट करता है। पढ़ें/लिखें float.

**रिटर्न:**
float

### setEndPosAlpha(float value) {#setEndPosAlpha-float-}
```
public final void setEndPosAlpha(float value)
```

अंत अल्फा मान (प्रतिशत) के अल्फा ग्रेडिएंट रैंप के साथ अंत स्थिति को निर्दिष्ट करता है। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getFadeDirection() {#getFadeDirection--}
```
public final float getFadeDirection()
```

परावर्तन को ऑफ़सेट करने की दिशा को निर्दिष्ट करता है। (कोण) पढ़ें/लिखें float.

**रिटर्न:**
float

### setFadeDirection(float value) {#setFadeDirection-float-}
```
public final void setFadeDirection(float value)
```

परावर्तन को ऑफ़सेट करने की दिशा को निर्दिष्ट करता है। (कोण) पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getStartReflectionOpacity() {#getStartReflectionOpacity--}
```
public final float getStartReflectionOpacity()
```

परावर्तन की प्रारंभिक अस्पृष्टता। (प्रतिशत) पढ़ें/लिखें float.

**रिटर्न:**
float

### setStartReflectionOpacity(float value) {#setStartReflectionOpacity-float-}
```
public final void setStartReflectionOpacity(float value)
```

परावर्तन की प्रारंभिक अस्पृष्टता। (प्रतिशत) पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getEndReflectionOpacity() {#getEndReflectionOpacity--}
```
public final float getEndReflectionOpacity()
```

परावर्त

न की अंतिम अस्पृष्टता। (प्रतिशत) पढ़ें/लिखें float.

**रिटर्न:**
float

### setEndReflectionOpacity(float value) {#setEndReflectionOpacity-float-}
```
public final void setEndReflectionOpacity(float value)
```

परावर्तन की अंतिम अस्पृष्टता। (प्रतिशत) पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getBlurRadius() {#getBlurRadius--}
```
public final double getBlurRadius()
```

ब्लर त्रिज्या। पढ़ें/लिखें double.

**रिटर्न:**
double

### setBlurRadius(double value) {#setBlurRadius-double-}
```
public final void setBlurRadius(double value)
```

ब्लर त्रिज्या। पढ़ें/लिखें double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public final float getDirection()
```

परावर्तन की दिशा। पढ़ें/लिखें float.

**रिटर्न:**
float

### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

परावर्तन की दिशा। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public final double getDistance()
```

परावर्तन की दूरी। पढ़ें/लिखें double.

**रिटर्न:**
double

### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

परावर्तन की दूरी। पढ़ें/लिखें double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getRectangleAlign() {#getRectangleAlign--}
```
public final byte getRectangleAlign()
```

आयत संरेखण। पढ़ें/लिखें [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**रिटर्न:**
byte

### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public final void setRectangleAlign(byte value)
```

आयत संरेखण। पढ़ें/लिखें [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public final double getSkewHorizontal()
```

क्षैतिज स्क्यू कोण को निर्दिष्ट करता है। पढ़ें/लिखें double.

**रिटर्न:**
double

### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public final void setSkewHorizontal(double value)
```

क्षैतिज स्क्यू कोण को निर्दिष्ट करता है। पढ़ें/लिखें double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public final double getSkewVertical()
```

ऊर्ध्वाधर स्क्यू कोण को निर्दिष्ट करता है। पढ़ें/लिखें double.

**रिटर्न:**
double

### setSkewVertical(double value) {#setSkewVertical-double-}
```
public final void setSkewVertical(double value)
```

ऊर्ध्वाधर स्क्यू कोण को निर्दिष्ट करता है। पढ़ें/लिखें double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public final boolean getRotateShadowWithShape()
```

यदि आकार घुमाया गया है, तो परावर्तन को आकार के साथ घुमाना चाहिए या नहीं, इसे निर्दिष्ट करता है। पढ़ें/लिखें boolean.

**रिटर्न:**
boolean

### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public final void setRotateShadowWithShape(boolean value)
```

यदि आकार घुमाया गया है, तो परावर्तन को आकार के साथ घुमाना चाहिए या नहीं, इसे निर्दिष्ट करता है। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public final double getScaleHorizontal()
```

क्षैतिज स्केलिंग कारक को निर्दिष्ट करता है, नकारात्मक स्केलिंग फ्लिप का कारण बनती है। (प्रतिशत) पढ़ें/लिखें double.

**रिटर्न:**
double

### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public final void setScaleHorizontal(double value)
```

क्षैतिज स्केलिंग कारक को निर्दिष्ट करता है, नकारात्मक स्केलिंग फ्लिप का कारण बनती है। (प्रतिशत) पढ़ें/लिखें double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public final double getScaleVertical()
```

ऊर्ध्वाधर स्केलिंग कारक को निर्दिष्ट करता है, नकारात्मक स्केलिंग फ्लिप का कारण बनती है। (प्रतिशत) पढ़ें/लिखें double.

**रिटर्न:**
double

### setScaleVertical(double value) {#setScaleVertical-double-}
```
public final void setScaleVertical(double value)
```

ऊर्ध्वाधर स्केलिंग कारक को निर्दिष्ट करता है, नकारात्मक स्केलिंग फ्लिप का कारण बनती है। (प्रतिशत) पढ़ें/लिखें double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getEffective() {#getEffective--}
```
public final IReflectionEffectiveData getEffective()
```

विरासत लागू होने के साथ प्रभावी Reflection प्रभाव डेटा प्राप्त करता है।

**रिटर्न:**
[IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata) - A [IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata).

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य IDOMObject.

**रिटर्न:**
com.aspose.slides.IDOMObject

### getVersion() {#getVersion--}
```
public final long getVersion()
```

संस्करण। केवल-पढ़ने योग्य long.

**रिटर्न:**
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

parent IPresentationComponent लौटाता है। केवल-पढ़ने योग्य [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**रिटर्न:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

निर्धारित करता है कि निर्दिष्ट [Reflection](../../com.aspose.slides/reflection) वर्तमान [Reflection](../../com.aspose.slides/reflection) के बराबर है या नहीं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | तुलना करने के लिए [Reflection](../../com.aspose.slides/reflection)। |

**रिटर्न:**
boolean - true यदि वस्तुएँ बराबर हैं; अन्यथा false.

### hashCode() {#hashCode--}
```
public boolean equals(Object obj)
```

किसी विशिष्ट प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है।

**रिटर्न:**
int - वर्तमान वस्तु का हैश कोड।