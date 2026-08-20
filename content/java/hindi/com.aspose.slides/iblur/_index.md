---
title: IBlur
second_title: Aspose.Slides for Java API संदर्भ
description: पूरे आकार पर लागू ब्लर प्रभाव को दर्शाता है, जिसमें उसका फ़िल भी शामिल है।
type: docs
url: /hi/com.aspose.slides/iblur/
---
**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IBlur extends IImageTransformOperation, IAccessiblePVIObject<IBlurEffectiveData>
```

पूरे आकार पर लागू ब्लर प्रभाव को दर्शाता है, जिसमें उसका फ़िल भी शामिल है। सभी रंग चैनल, जिसमें अल्फा भी शामिल है, प्रभावित होते हैं।

## विधियां

| विधि | विवरण |
| --- | --- |
| [getRadius()](#getRadius--) | ब्लर त्रिज्या को लौटाता या सेट करता है। |
| [setRadius(double value)](#setRadius-double-) | ब्लर त्रिज्या को लौटाता या सेट करता है। |
| [getGrow()](#getGrow--) | निर्धारित करता है कि ब्लरिंग के परिणामस्वरूप ऑब्जेक्ट की सीमाएँ बढ़नी चाहिए या नहीं। |
| [setGrow(boolean value)](#setGrow-boolean-) | निर्धारित करता है कि ब्लरिंग के परिणामस्वरूप ऑब्जेक्ट की सीमाएँ बढ़नी चाहिए या नहीं। |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

ब्लर त्रिज्या को लौटाता या सेट करता है। पढ़ने/लिखने योग्य डबल।

**रिटर्न:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```

ब्लर त्रिज्या को लौटाता या सेट करता है। पढ़ने/लिखने योग्य डबल।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | double |  |
### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

निर्धारित करता है कि ब्लरिंग के परिणामस्वरूप ऑब्जेक्ट की सीमाएँ बढ़नी चाहिए या नहीं। True संकेत देता है कि सीमाएँ बढ़ाई गई हैं जबकि false संकेत देता है कि नहीं। पढ़ने/लिखने योग्य बूलियन।

**रिटर्न:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public abstract void setGrow(boolean value)
```

निर्धारित करता है कि ब्लरिंग के परिणामस्वरूप ऑब्जेक्ट की सीमाएँ बढ़नी चाहिए या नहीं। True संकेत देता है कि सीमाएँ बढ़ाई गई हैं जबकि false संकेत देता है कि नहीं। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |