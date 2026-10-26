---
title: IMotionEffect
second_title: Aspose.Slides Android के लिए - Java API रेफ़रेंस के द्वारा
description: इफ़ेक्ट के मोशन इफ़ेक्ट व्यवहार का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/imotioneffect/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IMotionEffect extends IBehavior
```

प्रभाव की मोशन इफ़ेक्ट व्यवहार को दर्शाता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getFrom()](#getFrom--) | एनिमेशन को शुरू करने के लिए x/y निर्देशांक (प्रतिशत में) निर्दिष्ट करता है। |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | एनिमेशन को शुरू करने के लिए x/y निर्देशांक (प्रतिशत में) निर्दिष्ट करता है। |
| [getTo()](#getTo--) | एनिमेशन मोशन इफ़ेक्ट के लिए लक्ष्य स्थान (प्रतिशत में) निर्दिष्ट करता है। |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | एनिमेशन मोशन इफ़ेक्ट के लिए लक्ष्य स्थान (प्रतिशत में) निर्दिष्ट करता है। |
| [getBy()](#getBy--) | एनिमेशन के लिए सापेक्ष ऑफ़सेट मान (प्रतिशत में) वर्णन करता है। |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | एनिमेशन के लिए सापेक्ष ऑफ़सेट मान (प्रतिशत में) वर्णन करता है। |
| [getRotationCenter()](#getRotationCenter--) | X कोण द्वारा मोशन पाथ को घुमाने के लिए उपयोग किए जाने वाले घूर्णन केंद्र का वर्णन करता है। |
| [setRotationCenter(PointF value)](#setRotationCenter-android.graphics.PointF-) | X कोण द्वारा मोशन पाथ को घुमाने के लिए उपयोग किए जाने वाले घूर्णन केंद्र का वर्णन करता है। |
| [getOrigin()](#getOrigin--) | स्लाइड के लेआउट या पैरेंट जैसी चीज़ों के सापेक्ष मोशन पाथ की उत्पत्ति क्या है, यह निर्दिष्ट करता है। |
| [setOrigin(int value)](#setOrigin-int-) | स्लाइड के लेआउट या पैरेंट जैसी चीज़ों के सापेक्ष मोशन पाथ की उत्पत्ति क्या है, यह निर्दिष्ट करता है। |
| [getPath()](#getPath--) | एनिमेशन मोशन के लिए निर्देशांक के साथ पाथ प्रिमिटिव निर्दिष्ट करता है। |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | एनिमेशन मोशन के लिए निर्देशांक के साथ पाथ प्रिमिटिव निर्दिष्ट करता है। |
| [getPathEditMode()](#getPathEditMode--) | शेप के मूव होने पर मोशन पाथ कैसे चलता है, यह निर्दिष्ट करता है। |
| [setPathEditMode(int value)](#setPathEditMode-int-) | शेप के मूव होने पर मोशन पाथ कैसे चलता है, यह निर्दिष्ट करता है। |
| [getAngle()](#getAngle--) | मोशन पाथ का सापेक्ष कोण वर्णन करता है। |
| [setAngle(float value)](#setAngle-float-) | मोशन पाथ का सापेक्ष कोण वर्णन करता है। |
### getFrom() {#getFrom--}
```
public abstract PointF getFrom()
```

एनिमेशन को शुरू करने के लिए x/y निर्देशांक (प्रतिशत में) निर्दिष्ट करता है। पढ़ें/लिखें android.graphics.PointF.

**वापसी:**
android.graphics.PointF
### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public abstract void setFrom(PointF value)
```

एनिमेशन को शुरू करने के लिए x/y निर्देशांक (प्रतिशत में) निर्दिष्ट करता है। पढ़ें/लिखें android.graphics.PointF.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getTo() {#getTo--}
```
public abstract PointF getTo()
```

एनिमेशन मोशन इफ़ेक्ट के लिए लक्ष्य स्थान (प्रतिशत में) निर्दिष्ट करता है। पढ़ें/लिखें android.graphics.PointF.

**वापसी:**
android.graphics.PointF
### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public abstract void setTo(PointF value)
```

एनिमेशन मोशन इफ़ेक्ट के लिए लक्ष्य स्थान (प्रतिशत में) निर्दिष्ट करता है। पढ़ें/लिखें android.graphics.PointF.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getBy() {#getBy--}
```
public abstract PointF getBy()
```

एनिमेशन के लिए सापेक्ष ऑफ़सेट मान (प्रतिशत में) वर्णन करता है। पढ़ें/लिखें android.graphics.PointF.

**वापसी:**
android.graphics.PointF
### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public abstract void setBy(PointF value)
```

एनिमेशन के लिए सापेक्ष ऑफ़सेट मान (प्रतिशत में) वर्णन करता है। पढ़ें/लिखें android.graphics.PointF.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getRotationCenter() {#getRotationCenter--}
```
public abstract PointF getRotationCenter()
```

X कोण द्वारा मोशन पाथ को घुमाने के लिए उपयोग किए जाने वाले घूर्णन केंद्र का वर्णन करता है। पढ़ें/लिखें android.graphics.PointF.

**वापसी:**
android.graphics.PointF
### setRotationCenter(PointF value) {#setRotationCenter-android.graphics.PointF-}
```
public abstract void setRotationCenter(PointF value)
```

X कोण द्वारा मोशन पाथ को घुमाने के लिए उपयोग किए जाने वाले घूर्णन केंद्र का वर्णन करता है। पढ़ें/लिखें android.graphics.PointF.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```

स्लाइड के लेआउट या पैरेंट जैसी चीज़ों के सापेक्ष मोशन पाथ की उत्पत्ति क्या है, यह निर्दिष्ट करता है। पढ़ें/लिखें [MotionOriginType](../../com.aspose.slides/motionorigintype).

**वापसी:**
int
### setOrigin(int value) {#setOrigin-int-}
```
public abstract void setOrigin(int value)
```

स्लाइड के लेआउट या पैरेंट जैसी चीज़ों के सापेक्ष मोशन पाथ की उत्पत्ति क्या है, यह निर्दिष्ट करता है। पढ़ें/लिखें [MotionOriginType](../../com.aspose.slides/motionorigintype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public abstract IMotionPath getPath()
```

एनिमेशन मोशन के लिए निर्देशांक के साथ पाथ प्रिमिटिव निर्दिष्ट करता है। पढ़ें/लिखें [IMotionPath](../../com.aspose.slides/imotionpath).

**वापसी:**
[IMotionPath](../../com.aspose.slides/imotionpath)
### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public abstract void setPath(IMotionPath value)
```

एनिमेशन मोशन के लिए निर्देशांक के साथ पाथ प्रिमिटिव निर्दिष्ट करता है। पढ़ें/लिखें [IMotionPath](../../com.aspose.slides/imotionpath).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public abstract int getPathEditMode()
```

शेप के मूव होने पर मोशन पाथ कैसे चलता है, यह निर्दिष्ट करता है। पढ़ें/लिखें [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**वापसी:**
int
### setPathEditMode(int value) {#setPathEditMode-int-}
```
public abstract void setPathEditMode(int value)
```

शेप के मूव होने पर मोशन पाथ कैसे चलता है, यह निर्दिष्ट करता है। पढ़ें/लिखें [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public abstract float getAngle()
```

मोशन पाथ का सापेक्ष कोण वर्णन करता है। पढ़ें/लिखें float.

**वापसी:**
float
### setAngle(float value) {#setAngle-float-}
```
public abstract void setAngle(float value)
```

मोशन पाथ का सापेक्ष कोण वर्णन करता है। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |