---
title: Reflection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
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

Represents a Reflection effect.
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getStartPosAlpha()](#getStartPosAlpha--) | स्टार्ट अल्फा मान (प्रतिशत) के अल्फा ग्रेडिएंट रैंप पर स्टार्ट स्थिति को निर्दिष्ट करता है। |
| [setStartPosAlpha(float value)](#setStartPosAlpha-float-) | स्टार्ट अल्फा मान (प्रतिशत) के अल्फा ग्रेडिएंट रैंप पर स्टार्ट स्थिति को निर्दिष्ट करता है। |
| [getEndPosAlpha()](#getEndPosAlpha--) | एंड अल्फा मान (प्रतिशत) के अल्फा ग्रेडिएंट रैंप पर एंड स्थिति को निर्दिष्ट करता है। |
| [setEndPosAlpha(float value)](#setEndPosAlpha-float-) | एंड अल्फा मान (प्रतिशत) के अल्फा ग्रेडिएंट रैंप पर एंड स्थिति को निर्दिष्ट करता है। |
| [getFadeDirection()](#getFadeDirection--) | रिफ्लेक्शन को ऑफ़सेट करने की दिशा को निर्दिष्ट करता है। |
| [setFadeDirection(float value)](#setFadeDirection-float-) | रिफ्लेक्शन को ऑफ़सेट करने की दिशा को निर्दिष्ट करता है। |
| [getStartReflectionOpacity()](#getStartReflectionOpacity--) | प्रारंभिक रिफ्लेक्शन अस्पष्टता। |
| [setStartReflectionOpacity(float value)](#setStartReflectionOpacity-float-) | प्रारंभिक रिफ्लेक्शन अस्पष्टता। |
| [getEndReflectionOpacity()](#getEndReflectionOpacity--) | अंतिम रिफ्लेक्शन अस्पष्टता। |
| [setEndReflectionOpacity(float value)](#setEndReflectionOpacity-float-) | अंतिम रिफ्लेक्शन अस्पष्टता। |
| [getBlurRadius()](#getBlurRadius--) | ब्लर रेडियस। |
| [setBlurRadius(double value)](#setBlurRadius-double-) | ब्लर रेडियस। |
| [getDirection()](#getDirection--) | रिफ्लेक्शन की दिशा। |
| [setDirection(float value)](#setDirection-float-) | रिफ्लेक्शन की दिशा। |
| [getDistance()](#getDistance--) | रिफ्लेक्शन की दूरी। |
| [setDistance(double value)](#setDistance-double-) | रिफ्लेक्शन की दूरी। |
| [getRectangleAlign()](#getRectangleAlign--) | आयत संरेखण। |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | आयत संरेखण। |
| [getSkewHorizontal()](#getSkewHorizontal--) | क्षैतिज स्क्यू कोण को निर्दिष्ट करता है। |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | क्षैतिज स्क्यू कोण को निर्दिष्ट करता है। |
| [getSkewVertical()](#getSkewVertical--) | ऊर्ध्वाधर स्क्यू कोण को निर्दिष्ट करता है। |
| [setSkewVertical(double value)](#setSkewVertical-double-) | ऊर्ध्वाधर स्क्यू कोण को निर्दिष्ट करता है। |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | यदि आकार घुमा हुआ है तो रिफ्लेक्शन को आकार के साथ घुमाने की आवश्यकता है या नहीं, इसे निर्दिष्ट करता है। |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | यदि आकार घुमा हुआ है तो रिफ्लेक्शन को आकार के साथ घुमाने की आवश्यकता है या नहीं, इसे निर्दिष्ट करता है। |
| [getScaleHorizontal()](#getScaleHorizontal--) | क्षैतिज स्केलिंग फ़ैक्टर को निर्दिष्ट करता है, नकारात्मक स्केलिंग फ्लिप का कारण बनती है। |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | क्षैतिज स्केलिंग फ़ैक्टर को निर्दिष्ट करता है, नकारात्मक स्केलिंग फ्लिप का कारण बनती है। |
| [getScaleVertical()](#getScaleVertical--) | ऊर्ध्वाधर स्केलिंग फ़ैक्टर को निर्दिष्ट करता है, नकारात्मक स्केलिंग फ्लिप का कारण बनती है। |
| [setScaleVertical(double value)](#setScaleVertical-double-) | ऊर्ध्वाधर स्केलिंग फ़ैक्टर को निर्दिष्ट करता है, नकारात्मक स्केलिंग फ्लिप का कारण बनती है। |
| [getEffective()](#getEffective--) | विरासत लागू होने के साथ प्रभावी Reflection डेटा प्राप्त करता है। |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि निर्दिष्ट [Reflection](../../com.aspose.slides/reflection) वर्तमान [Reflection](../../com.aspose.slides/reflection) के बराबर है या नहीं। |
| [hashCode()](#hashCode--) | किसी विशेष प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है। |
### getStartPosAlpha() {#getStartPosAlpha--}
```
public final float getStartPosAlpha()
```

स्टार्ट अल्फा मान (प्रतिशत) के अल्फा ग्रेडिएंट रैंप पर स्टार्ट स्थिति को निर्दिष्ट करता है। पढ़ें/लिखें float।

**रिटर्न:**
float
### setStartPosAlpha(float value) {#setStartPosAlpha-float-}
```
public final void setStartPosAlpha(float value)
```

स्टार्ट अल्फा मान (प्रतिशत) के अल्फा ग्रेडिएंट रैंप पर स्टार्ट स्थिति को निर्दिष्ट करता है। पढ़ें/लिखें float।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getEndPosAlpha() {#getEndPosAlpha--}
```
public final float getEndPosAlpha()
```

एंड अल्फा मान (प्रतिशत) के अल्फा ग्रेडिएंट रैंप पर एंड स्थिति को निर्दिष्ट करता है। पढ़ें/लिखें float।

**रिटर्न:**
float
### setEndPosAlpha(float value) {#setEndPosAlpha-float-}
```
public final void setEndPosAlpha(float value)
```

एंड अल्फा मान (प्रतिशत) के अल्फा ग्रेडिएंट रैंप पर एंड स्थिति को निर्दिष्ट करता है। पढ़ें/लिखें float।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getFadeDirection() {#getFadeDirection--}
```
public final float getFadeDirection()
```

रिफ्लेक्शन को ऑफ़सेट करने की दिशा (कोन) को निर्दिष्ट करता है। पढ़ें/लिखें float।

**रिटर्न:**
float
### setFadeDirection(float value) {#setFadeDirection-float-}
```
public final void setFadeDirection(float value)
```

रिफ्लेक्शन को ऑफ़सेट करने की दिशा (कोन) को निर्दिष्ट करता है। पढ़ें/लिखें float।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getStartReflectionOpacity() {#getStartReflectionOpacity--}
```
public final float getStartReflectionOpacity()
```

प्रारंभिक रिफ्लेक्शन अस्पष्टता (प्रतिशत)। पढ़ें/लिखें float।

**रिटर्न:**
float
### setStartReflectionOpacity(float value) {#setStartReflectionOpacity-float-}
```
public final void setStartReflectionOpacity(float value)
```

प्रारंभिक रिफ्लेक्शन अस्पष्टता (प्रतिशत)। पढ़ें/लिखें float।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getEndReflectionOpacity() {#getEndReflectionOpacity--}
```
public final float getEndReflectionOpacity()
```

अंतिम रिफ्लेक्शन अस्पष्टता (प्रतिशत)। पढ़ें/लिखें float।

**रिटर्न:**
float
### setEndReflectionOpacity(float value) {#setEndReflectionOpacity-float-}
```
public final void setEndReflectionOpacity(float value)
```

अंतिम रिफ्लेक्शन अस्पष्टता (प्रतिशत)। पढ़ें/लिखें float।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getBlurRadius() {#getBlurRadius--}
```
public final double getBlurRadius()
```

ब्लर रेडियस। पढ़ें/लिखें double।

**रिटर्न:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public final void setBlurRadius(double value)
```

ब्लर रेडियस। पढ़ें/लिखें double।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public final float getDirection()
```

रिफ्लेक्शन की दिशा। पढ़ें/लिखें float।

**रिटर्न:**
float
### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

रिफ्लेक्शन की दिशा। पढ़ें/लिखें float।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public final double getDistance()
```

रिफ्लेक्शन की दूरी। पढ़ें/लिखें double।

**रिटर्न:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

रिफ्लेक्शन की दूरी। पढ़ें/लिखें double।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getRectangleAlign() {#getRectangleAlign--}
```
public final byte getRectangleAlign()
```

आयत संरेखण। पढ़ें/लिखें [RectangleAlignment](../../com.aspose.slides/rectanglealignment)।

**रिटर्न:**
byte
### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public final void setRectangleAlign(byte value)
```

आयत संरेखण। पढ़ें/लिखें [RectangleAlignment](../../com.aspose.slides/rectanglealignment)।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public final double getSkewHorizontal()
```

क्षैतिज स्क्यू कोण को निर्दिष्ट करता है। पढ़ें/लिखें double।

**रिटर्न:**
double
### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public final void setSkewHorizontal(double value)
```

क्षैतिज स्क्यू कोण को निर्दिष्ट करता है। पढ़ें/लिखें double।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public final double getSkewVertical()
```

ऊर्ध्वाधर स्क्यू कोण को निर्दिष्ट करता है। पढ़ें/लिखें double।

**रिटर्न:**
double
### setSkewVertical(double value) {#setSkewVertical-double-}
```
public final void setSkewVertical(double value)
```

ऊर्ध्वाधर स्क्यू कोण को निर्दिष्ट करता है। पढ़ें/लिखें double।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public final boolean getRotateShadowWithShape()
```

यदि आकार घुमा हुआ है तो रिफ्लेक्शन को आकार के साथ घुमाने की आवश्यकता है या नहीं, इसे निर्दिष्ट करता है। पढ़ें/लिखें boolean।

**रिटर्न:**
boolean
### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public final void setRotateShadowWithShape(boolean value)
```

यदि आकार घुमा हुआ है तो रिफ्लेक्शन को आकार के साथ घुमाने की आवश्यकता है या नहीं, इसे निर्दिष्ट करता है। पढ़ें/लिखें boolean।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public final double getScaleHorizontal()
```

क्षैतिज स्केलिंग फैक्टर को निर्दिष्ट करता है, नकारात्मक स्केलिंग फ्लिप का कारण बनती है। (प्रतिशत) पढ़ें/लिखें double।

**रिटर्न:**
double
### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public final void setScaleHorizontal(double value)
```

क्षैतिज स्केलिंग फैक्टर को निर्दिष्ट करता है, नकारात्मक स्केलिंग फ्लिप का कारण बनती है। (प्रतिशत) पढ़ें/लिखें double।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public final double getScaleVertical()
```

ऊर्ध्वाधर स्केलिंग फैक्टर को निर्दिष्ट करता है, नकारात्मक स्केलिंग फ्लिप का कारण बनती है। (प्रतिशत) पढ़ें/लिखें double।

**रिटर्न:**
double
### setScaleVertical(double value) {#setScaleVertical-double-}
```
public final void setScaleVertical(double value)
```

ऊर्ध्वाधर स्केलिंग फैक्टर को निर्दिष्ट करता है, नकारात्मक स्केलिंग फ्लिप का कारण बनती है। (प्रतिशत) पढ़ें/लिखें double।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getEffective() {#getEffective--}
```
public final IReflectionEffectiveData getEffective()
```

विरासत लागू होने के साथ प्रभावी Reflection डेटा प्राप्त करता है।

**रिटर्न:**
[IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata) - एक [IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata)।
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने-योग्य IDOMObject।

**रिटर्न:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

संस्करण। केवल-पढ़ने-योग्य long।

**रिटर्न:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

parent IPresentationComponent लौटाता है। केवल-पढ़ने-योग्य [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)।

**रिटर्न:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

निर्धारित करता है कि निर्दिष्ट [Reflection](../../com.aspose.slides/reflection) वर्तमान [Reflection](../../com.aspose.slides/reflection) के बराबर है या नहीं।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | तुलना करने के लिए [Reflection](../../com.aspose.slides/reflection)। |

**रिटर्न:**
boolean - true यदि ऑब्जेक्ट समान हैं; अन्यथा, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

एक विशिष्ट प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है।

**रिटर्न:**
int - वर्तमान ऑब्जेक्ट के लिए एक हैश कोड।