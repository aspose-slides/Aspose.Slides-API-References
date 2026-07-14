---
title: IBlur
second_title: Aspose.Slides for Android द्वारा Java API संदर्भ
description: पूरे आकार, जिसमें इसका भराव शामिल है, पर लागू किए जाने वाले ब्लर प्रभाव का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/iblur/
---
**All Implemented Interfaces:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IBlur extends IImageTransformOperation, IAccessiblePVIObject<IBlurEffectiveData>
```

Represents a Blur effect that is applied to the entire shape, including its fill. All color channels, including alpha, are affected.
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getRadius()](#getRadius--) | ब्लर त्रिज्या को प्राप्त करता है या सेट करता है। |
| [setRadius(double value)](#setRadius-double-) | ब्लर त्रिज्या को प्राप्त करता है या सेट करता है। |
| [getGrow()](#getGrow--) | निर्धारित करता है कि ब्लरिंग के परिणामस्वरूप वस्तु की सीमाएँ बढ़नी चाहिए या नहीं। |
| [setGrow(boolean value)](#setGrow-boolean-) | निर्धारित करता है कि ब्लरिंग के परिणामस्वरूप वस्तु की सीमाएँ बढ़नी चाहिए या नहीं। |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


ब्लर त्रिज्या को प्राप्त करता है या सेट करता है। पढ़ें/लिखें double.

**वापसी:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```


ब्लर त्रिज्या को प्राप्त करता है या सेट करता है। पढ़ें/लिखें double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```


निर्धारित करता है कि ब्लरिंग के परिणामस्वरूप वस्तु की सीमाएँ बढ़नी चाहिए या नहीं। सही (true) दर्शाता है कि सीमाएँ बढ़ाई गई हैं जबकि गलत (false) दर्शाता है कि वे नहीं बढ़ी हैं। पढ़ें/लिखें boolean.

**वापसी:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public abstract void setGrow(boolean value)
```


निर्धारित करता है कि ब्लरिंग के परिणामस्वरूप वस्तु की सीमाएँ बढ़नी चाहिए या नहीं। सही (true) दर्शाता है कि सीमाएँ बढ़ाई गई हैं जबकि गलत (false) दर्शाता है कि वे नहीं बढ़ी हैं। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |