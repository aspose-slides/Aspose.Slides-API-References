---
title: IBlurEffectiveData
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक अपरिवर्तनीय वस्तु जो पूरे आकार पर लागू किए जाने वाले ब्लर प्रभाव का प्रतिनिधित्व करती है, जिसमें उसका भराव भी शामिल है।
type: docs
url: /hi/com.aspose.slides/iblureffectivedata/
---
**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBlurEffectiveData extends IEffectEffectiveData
```

एक अपरिवर्तनीय वस्तु जो पूरे आकार पर लागू किए जाने वाले Blur प्रभाव का प्रतिनिधित्व करती है, जिसमें उसका भराव भी शामिल है। सभी रंग चैनल, अल्फा सहित, प्रभावित होते हैं।  

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getRadius()](#getRadius--) | ब्लर त्रिज्या को प्राप्त करता है या सेट करता है। |
| [getGrow()](#getGrow--) | निर्धारित करता है कि ब्लरिंग के परिणामस्वरूप वस्तु की सीमाएँ बढ़नी चाहिए या नहीं। |

### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

ब्लर त्रिज्या को प्राप्त करता है या सेट करता है। केवल-पढ़ने योग्य double.

**वापसी:**
double

### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

निर्धारित करता है कि ब्लरिंग के परिणामस्वरूप वस्तु की सीमाएँ बढ़नी चाहिए या नहीं। True संकेत करता है कि सीमाएँ बढ़ती हैं जबकि false संकेत करता है कि वे नहीं बढ़तीं। केवल-पढ़ने योग्य boolean.

**वापसी:**
boolean