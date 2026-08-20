---
title: IMotionEffect
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: इफ़ेक्ट के मोशन इफ़ेक्ट व्यवहार को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/imotioneffect/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IMotionEffect extends IBehavior
```

इफ़ेक्ट के मोशन इफ़ेक्ट व्यवहार को दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getFrom()](#getFrom--) | एनिमेशन शुरू करने के लिए एक x/y निर्देशांक निर्दिष्ट करता है (प्रतिशत में)। |
| [setFrom(Point2D.Float value)](#setFrom-java.awt.geom.Point2D.Float-) | एनिमेशन शुरू करने के लिए एक x/y निर्देशांक निर्दिष्ट करता है (प्रतिशत में)। |
| [getTo()](#getTo--) | एनिमेशन मोशन इफ़ेक्ट के लिए लक्ष्य स्थान निर्दिष्ट करता है (प्रतिशत में)। |
| [setTo(Point2D.Float value)](#setTo-java.awt.geom.Point2D.Float-) | एनिमेशन मोशन इफ़ेक्ट के लिए लक्ष्य स्थान निर्दिष्ट करता है (प्रतिशत में)। |
| [getBy()](#getBy--) | एनिमेशन के लिए सापेक्ष ऑफ़सेट मान का वर्णन करता है (प्रतिशत में)। |
| [setBy(Point2D.Float value)](#setBy-java.awt.geom.Point2D.Float-) | एनिमेशन के लिए सापेक्ष ऑफ़सेट मान का वर्णन करता है (प्रतिशत में)। |
| [getRotationCenter()](#getRotationCenter--) | X कोण द्वारा मोशन पाथ को घुमाने के लिए उपयोग किए जाने वाले घूर्णन केंद्र का वर्णन करता है। |
| [setRotationCenter(Point2D.Float value)](#setRotationCenter-java.awt.geom.Point2D.Float-) | X कोण द्वारा मोशन पाथ को घुमाने के लिए उपयोग किए जाने वाले घूर्णन केंद्र का वर्णन करता है। |
| [getOrigin()](#getOrigin--) | स्लाइड के लेआउट या पैरेंट जैसी चीज़ों के सापेक्ष मोशन पाथ के मूल को निर्दिष्ट करता है। |
| [setOrigin(int value)](#setOrigin-int-) | स्लाइड के लेआउट या पैरेंट जैसी चीज़ों के सापेक्ष मोशन पाथ के मूल को निर्दिष्ट करता है। |
| [getPath()](#getPath--) | एनिमेशन मोशन के लिए निर्देशांक के साथ पाथ प्रिमिटिव को निर्दिष्ट करता है। |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | एनिमेशन मोशन के लिए निर्देशांक के साथ पाथ प्रिमिटिव को निर्दिष्ट करता है। |
| [getPathEditMode()](#getPathEditMode--) | आकार के स्थानांतरित होने पर मोशन पाथ कैसे चलता है, इसे निर्दिष्ट करता है। |
| [setPathEditMode(int value)](#setPathEditMode-int-) | आकार के स्थानांतरित होने पर मोशन पाथ कैसे चलता है, इसे निर्दिष्ट करता है। |
| [getAngle()](#getAngle--) | मोशन पाथ के सापेक्ष कोण का वर्णन करता है। |
| [setAngle(float value)](#setAngle-float-) | मोशन पाथ के सापेक्ष कोण का वर्णन करता है। |
### getFrom() {#getFrom--}
```
public abstract Point2D.Float getFrom()
```

एनिमेशन शुरू करने के लिए एक x/y निर्देशांक निर्दिष्ट करता है (प्रतिशत में)। पढ़ें/लिखें java.awt.geom.Point2D.Float.

**वापसी:**
java.awt.geom.Point2D.Float
### setFrom(Point2D.Float value) {#setFrom-java.awt.geom.Point2D.Float-}
```
public abstract void setFrom(Point2D.Float value)
```

एनिमेशन शुरू करने के लिए एक x/y निर्देशांक निर्दिष्ट करता है (प्रतिशत में)। पढ़ें/लिखें java.awt.geom.Point2D.Float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |
### getTo() {#getTo--}
```
public abstract Point2D.Float getTo()
```

एनिमेशन मोशन इफ़ेक्ट के लिए लक्ष्य स्थान निर्दिष्ट करता है (प्रतिशत में)। पढ़ें/लिखें java.awt.geom.Point2D.Float.

**वापसी:**
java.awt.geom.Point2D.Float
### setTo(Point2D.Float value) {#setTo-java.awt.geom.Point2D.Float-}
```
public abstract void setTo(Point2D.Float value)
```

एनिमेशन मोशन इफ़ेक्ट के लिए लक्ष्य स्थान निर्दिष्ट करता है (प्रतिशत में)। पढ़ें/लिखें java.awt.geom.Point2D.Float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |
### getBy() {#getBy--}
```
public abstract Point2D.Float getBy()
```

एनिमेशन के लिए सापेक्ष ऑफ़सेट मान का वर्णन करता है (प्रतिशत में)। पढ़ें/लिखें java.awt.geom.Point2D.Float.

**वापसी:**
java.awt.geom.Point2D.Float
### setBy(Point2D.Float value) {#setBy-java.awt.geom.Point2D.Float-}
```
public abstract void setBy(Point2D.Float value)
```

एनिमेशन के लिए सापेक्ष ऑफ़सेट मान का वर्णन करता है (प्रतिशत में)। पढ़ें/लिखें java.awt.geom.Point2D.Float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |
### getRotationCenter() {#getRotationCenter--}
```
public abstract Point2D.Float getRotationCenter()
```

X कोण द्वारा मोशन पाथ को घुमाने के लिए उपयोग किए जाने वाले घूर्णन केंद्र का वर्णन करता है। पढ़ें/लिखें java.awt.geom.Point2D.Float.

**वापसी:**
java.awt.geom.Point2D.Float
### setRotationCenter(Point2D.Float value) {#setRotationCenter-java.awt.geom.Point2D.Float-}
```
public abstract void setRotationCenter(Point2D.Float value)
```

X कोण द्वारा मोशन पाथ को घुमाने के लिए उपयोग किए जाने वाले घूर्णन केंद्र का वर्णन करता है। पढ़ें/लिखें java.awt.geom.Point2D.Float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |
### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```

स्लाइड के लेआउट या पैरेंट जैसी चीज़ों के सापेक्ष मोशन पाथ के मूल को निर्दिष्ट करता है। पढ़ें/लिखें [MotionOriginType](../../com.aspose.slides/motionorigintype).

**वापसी:**
int
### setOrigin(int value) {#setOrigin-int-}
```
public abstract void setOrigin(int value)
```

स्लाइड के लेआउट या पैरेंट जैसी चीज़ों के सापेक्ष मोशन पाथ के मूल को निर्दिष्ट करता है। पढ़ें/लिखें [MotionOriginType](../../com.aspose.slides/motionorigintype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getPath() {#getPath--}
```
public abstract IMotionPath getPath()
```

एनिमेशन मोशन के लिए निर्देशांक के साथ पाथ प्रिमिटिव को निर्दिष्ट करता है। पढ़ें/लिखें [IMotionPath](../../com.aspose.slides/imotionpath).

**वापसी:**
[IMotionPath](../../com.aspose.slides/imotionpath)
### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public abstract void setPath(IMotionPath value)
```

एनिमेशन मोशन के लिए निर्देशांक के साथ पाथ प्रिमिटिव को निर्दिष्ट करता है। पढ़ें/लिखें [IMotionPath](../../com.aspose.slides/imotionpath).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |
### getPathEditMode() {#getPathEditMode--}
```
public abstract int getPathEditMode()
```

आकार के स्थानांतरित होने पर मोशन पाथ कैसे चलता है, इसे निर्दिष्ट करता है। पढ़ें/लिखें [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**वापसी:**
int
### setPathEditMode(int value) {#setPathEditMode-int-}
```
public abstract void setPathEditMode(int value)
```

आकार के स्थानांतरित होने पर मोशन पाथ कैसे चलता है, इसे निर्दिष्ट करता है। पढ़ें/लिखें [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getAngle() {#getAngle--}
```
public abstract float getAngle()
```

मोशन पाथ के सापेक्ष कोण का वर्णन करता है। पढ़ें/लिखें float.

**वापसी:**
float
### setAngle(float value) {#setAngle-float-}
```
public abstract void setAngle(float value)
```

मोशन पाथ के सापेक्ष कोण का वर्णन करता है। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |