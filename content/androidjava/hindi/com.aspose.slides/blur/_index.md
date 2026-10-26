---
title: Blur
second_title: Aspose.Slides for Android के माध्यम से Java API संदर्भ
description: पूरे आकार पर, उसके भराव सहित, लागू किए गए ब्लर प्रभाव का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/blur/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.IBlur](../../com.aspose.slides/iblur), com.aspose.slides.IVisualEffect
```
public final class Blur extends ImageTransformOperation implements IBlur, IVisualEffect
```

पूरे आकार पर लागू ब्लर प्रभाव का प्रतिनिधित्व करता है, जिसमें उसका भराव भी शामिल है। सभी रंग चैनल, अल्फा सहित, प्रभावित होते हैं।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getRadius()](#getRadius--) | ब्लर त्रिज्या को लौटाता है या सेट करता है। |
| [setRadius(double value)](#setRadius-double-) | ब्लर त्रिज्या को लौटाता है या सेट करता है। |
| [getGrow()](#getGrow--) | निर्धरित करता है कि ब्लरिंग के परिणामस्वरूप ऑब्जेक्ट की सीमा को बढ़ाया जाना चाहिए या नहीं। |
| [setGrow(boolean value)](#setGrow-boolean-) | निर्धरित करता है कि ब्लरिंग के परिणामस्वरूप ऑब्जेक्ट की सीमा को बढ़ाया जाना चाहिए या नहीं। |
| [getEffective()](#getEffective--) | विरासत लागू करके प्रभावी ब्लर इफ़ेक्ट डेटा प्राप्त करता है। |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धरित करता है कि निर्दिष्ट [Blur](../../com.aspose.slides/blur) वर्तमान [Blur](../../com.aspose.slides/blur) के समान है या नहीं। |
| [hashCode()](#hashCode--) | किसी विशेष प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है। |
### getRadius() {#getRadius--}
```
public final double getRadius()
```

ब्लर त्रिज्या को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य double।

**रिटर्न:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

ब्लर त्रिज्या को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य double।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |
### getGrow() {#getGrow--}
```
public final boolean getGrow()
```

निर्धारित करता है कि ब्लरिंग के परिणामस्वरूप ऑब्जेक्ट की सीमा को बढ़ाया जाना चाहिए या नहीं। True संकेत देता है कि सीमाएँ बढ़ाई गई हैं जबकि false संकेत देता है कि वे नहीं बढ़ी हैं। पढ़ने/लिखने योग्य boolean।

**रिटर्न:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public final void setGrow(boolean value)
```

निर्धारित करता है कि ब्लरिंग के परिणामस्वरूप ऑब्जेक्ट की सीमा को बढ़ाया जाना चाहिए या नहीं। True संकेत देता है कि सीमाएँ बढ़ाई गई हैं जबकि false संकेत देता है कि वे नहीं बढ़ी हैं। पढ़ने/लिखने योग्य boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getEffective() {#getEffective--}
```
public final IBlurEffectiveData getEffective()
```

विरासत लागू करके प्रभावी ब्लर इफ़ेक्ट डेटा प्राप्त करता है।

**रिटर्न:**
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata) - A [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

निर्धारित करता है कि निर्दिष्ट [Blur](../../com.aspose.slides/blur) वर्तमान [Blur](../../com.aspose.slides/blur) के बराबर है या नहीं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | तुलना करने के लिए [Blur](../../com.aspose.slides/blur)। |

**रिटर्न:**
boolean - true यदि ऑब्जेक्ट समान हैं; अन्यथा false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

किसी विशेष प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है।

**रिटर्न:**
int - वर्तमान ऑब्जेक्ट के लिए एक हैश कोड।