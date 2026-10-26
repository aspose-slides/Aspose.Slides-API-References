---
title: IBlurEffectiveData
second_title: Aspose.Slides के लिए Java API संदर्भ
description: अपरिवर्तनीय ऑब्जेक्ट जो Blur प्रभाव का प्रतिनिधित्व करता है जो पूरे आकार पर लागू होता है, जिसमें इसका भरण भी शामिल है।
type: docs
url: /hi/com.aspose.slides/iblureffectivedata/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBlurEffectiveData extends IEffectEffectiveData
```

अपरिवर्तनीय ऑब्जेक्ट जो Blur प्रभाव का प्रतिनिधित्व करता है जो पूरे आकार पर लागू होता है, जिसमें इसका भरण भी शामिल है। सभी रंग चैनल, जिसमें अल्फा भी शामिल है, प्रभावित होते हैं।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getRadius()](#getRadius--) | blur radius को प्राप्त करता है या सेट करता है। |
| [getGrow()](#getGrow--) | निर्धारित करता है कि ब्लरिंग के परिणामस्वरूप वस्तु की सीमाएँ बढ़ाई जानी चाहिए या नहीं। |

### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

blur radius को प्राप्त करता है या सेट करता है। केवल पढ़ने योग्य double.

**वापसी:**
double

### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

निर्धारित करता है कि ब्लरिंग के परिणामस्वरूप वस्तु की सीमाएँ बढ़ाई जानी चाहिए या नहीं। True संकेत देता है कि सीमाएँ बढ़ाई गई हैं जबकि false संकेत देता है कि नहीं। केवल पढ़ने योग्य boolean.

**वापसी:**
boolean