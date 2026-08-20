---
title: Blur
second_title: Aspose.Slides for Java API संदर्भ
description: पूरे आकार पर, जिसमें उसका भराव भी शामिल है, लागू किए जाने वाले ब्लर प्रभाव का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/blur/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**सभी लागू किए गए इंटरफ़ेस:**  
[com.aspose.slides.IBlur](../../com.aspose.slides/iblur), com.aspose.slides.IVisualEffect  
```
public final class Blur extends ImageTransformOperation implements IBlur, IVisualEffect
```

पूरा आकार, जिसमें उसका भराव भी शामिल है, पर लागू किए जाने वाले ब्लर प्रभाव का प्रतिनिधित्व करता है। सभी रंग चैनल, अल्फा सहित, प्रभावित होते हैं।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getRadius()](#getRadius--) | ब्लर त्रिज्या को प्राप्त या सेट करता है। |
| [setRadius(double value)](#setRadius-double-) | ब्लर त्रिज्या को प्राप्त या सेट करता है। |
| [getGrow()](#getGrow--) | निर्धारित करता है कि ब्लरिंग के परिणामस्वरूप वस्तु की सीमाएँ बढ़ाई जानी चाहिए या नहीं। |
| [setGrow(boolean value)](#setGrow-boolean-) | निर्धारित करता है कि ब्लरिंग के परिणामस्वरूप वस्तु की सीमाएँ बढ़ाई जानी चाहिए या नहीं। |
| [getEffective()](#getEffective--) | विरासत लागू होने पर प्रभावी ब्लर प्रभाव डेटा प्राप्त करता है। |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि निर्दिष्ट [Blur](../../com.aspose.slides/blur) वर्तमान [Blur](../../com.aspose.slides/blur) के बराबर है या नहीं। |
| [hashCode()](#hashCode--) | किसी विशिष्ट प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है। |

### getRadius() {#getRadius--}
```
public final double getRadius()
```

ब्लर त्रिज्या को प्राप्त या सेट करता है। पढ़ें/लिखें double.

**वापसी:**  
double

### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

ब्लर त्रिज्या को प्राप्त या सेट करता है। पढ़ें/लिखें double.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public final boolean getGrow()
```

निर्धारित करता है कि ब्लरिंग के परिणामस्वरूप वस्तु की सीमाएँ बढ़ाई जानी चाहिए या नहीं। true का अर्थ है सीमाएँ बढ़ाई गईँ और false का अर्थ है नहीं। पढ़ें/लिखें boolean.

**वापसी:**  
boolean

### setGrow(boolean value) {#setGrow-boolean-}
```
public final void setGrow(boolean value)
```

निर्धारित करता है कि ब्लरिंग के परिणामस्वरूप वस्तु की सीमाएँ बढ़ाई जानी चाहिए या नहीं। true का अर्थ है सीमाएँ बढ़ाई गईँ और false का अर्थ है नहीं। पढ़ें/लिखें boolean.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final IBlurEffectiveData getEffective()
```

विरासत लागू होने पर प्रभावी ब्लर प्रभाव डेटा प्राप्त करता है।

**वापसी:**  
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata) - एक [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata)।

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

निर्धारित करता है कि निर्दिष्ट [Blur](../../com.aspose.slides/blur) वर्तमान [Blur](../../com.aspose.slides/blur) के बराबर है या नहीं।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | तुलना करने के लिए [Blur](../../com.aspose.slides/blur)। |

**वापसी:**  
boolean - यदि वस्तुएँ समान हैं तो true; अन्यथा false।

### hashCode() {#hashCode--}
```
public int hashCode()
```

किसी विशिष्ट प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है।

**वापसी:**  
int - वर्तमान वस्तु के लिए एक हैश कोड।