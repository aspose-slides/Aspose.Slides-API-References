---
title: IBehavior
second_title: Aspose.Slides for Java API Reference
description: इफ़ेक्ट का बेस क्लास व्यवहार दर्शाता है।
type: docs
url: /hi/com.aspose.slides/ibehavior/
---```
public interface IBehavior
```

इफ़ेक्ट का बेस क्लास व्यवहार दर्शाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getAccumulate()](#getAccumulate--) | यह दर्शाता है कि एनीमेशन व्यवहार संग्रहीत होते हैं या नहीं। |
| [setAccumulate(byte value)](#setAccumulate-byte-) | यह दर्शाता है कि एनीमेशन व्यवहार संग्रहीत होते हैं या नहीं। |
| [getAdditive()](#getAdditive--) | यह दर्शाता है कि वर्तमान एनीमेशन व्यवहार अन्य चल रहे एनीमेशन के साथ सम्मिलित है या नहीं। |
| [setAdditive(int value)](#setAdditive-int-) | यह दर्शाता है कि वर्तमान एनीमेशन व्यवहार अन्य चल रहे एनीमेशन के साथ सम्मिलित है या नहीं। |
| [getProperties()](#getProperties--) | यह व्यवहार की विशेषताओं को दर्शाता है। |
| [getTiming()](#getTiming--) | यह इफ़ेक्ट व्यवहार के टाइमिंग गुणों को दर्शाता है। |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | यह इफ़ेक्ट व्यवहार के टाइमिंग गुणों को दर्शाता है। |
### getAccumulate() {#getAccumulate--}
```
public abstract byte getAccumulate()
```

यह दर्शाता है कि एनीमेशन व्यवहार संग्रहीत होते हैं या नहीं। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool).

**वापसी मान:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public abstract void setAccumulate(byte value)
```

यह दर्शाता है कि एनीमेशन व्यवहार संग्रहीत होते हैं या नहीं। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getAdditive() {#getAdditive--}
```
public abstract int getAdditive()
```

यह दर्शाता है कि वर्तमान एनीमेशन व्यवहार अन्य चल रहे एनीमेशन के साथ सम्मिलित है या नहीं। पढ़ें/लिखें [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**वापसी मान:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public abstract void setAdditive(int value)
```

यह दर्शाता है कि वर्तमान एनीमेशन व्यवहार अन्य चल रहे एनीमेशन के साथ सम्मिलित है या नहीं। पढ़ें/लिखें [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getProperties() {#getProperties--}
```
public abstract IBehaviorPropertyCollection getProperties()
```

यह व्यवहार की विशेषताओं को दर्शाता है। केवल-पढ़ने योग्य [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**वापसी मान:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

यह इफ़ेक्ट व्यवहार के टाइमिंग गुणों को दर्शाता है। पढ़ें/लिखें [ITiming](../../com.aspose.slides/itiming).

**वापसी मान:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

यह इफ़ेक्ट व्यवहार के टाइमिंग गुणों को दर्शाता है। पढ़ें/लिखें [ITiming](../../com.aspose.slides/itiming).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |