---
title: IBehavior
second_title: Aspose.Slides for Android via Java API Reference
description: इफ़ेक्ट के बेस क्लास व्यवहार को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/ibehavior/
---```
public interface IBehavior
```

इफ़ेक्ट के बेस क्लास व्यवहार को दर्शाता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getAccumulate()](#getAccumulate--) | ऐनिमेशन व्यवहारों के संग्रहित होने की स्थिति को दर्शाता है। |
| [setAccumulate(byte value)](#setAccumulate-byte-) | ऐनिमेशन व्यवहारों के संग्रहित होने की स्थिति को दर्शाता है। |
| [getAdditive()](#getAdditive--) | वर्तमान ऐनिमेशन व्यवहार को अन्य चल रहे ऐनिमेशन्स के साथ संयोजित किया गया है या नहीं इसे दर्शाता है। |
| [setAdditive(int value)](#setAdditive-int-) | वर्तमान ऐनिमेशन व्यवहार को अन्य चल रहे ऐनिमेशन्स के साथ संयोजित किया गया है या नहीं इसे दर्शाता है। |
| [getProperties()](#getProperties--) | व्यवहार के गुणों को दर्शाता है। |
| [getTiming()](#getTiming--) | इफ़ेक्ट व्यवहार के लिए टाइमिंग गुणों को दर्शाता है। |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | इफ़ेक्ट व्यवहार के लिए टाइमिंग गुणों को दर्शाता है। |
### getAccumulate() {#getAccumulate--}
```
public abstract byte getAccumulate()
```


ऐनिमेशन व्यवहारों के संग्रहित होने की स्थिति को दर्शाता है। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool).

**रिटर्न:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public abstract void setAccumulate(byte value)
```


ऐनिमेशन व्यवहारों के संग्रहित होने की स्थिति को दर्शाता है। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool).

**पैरामीटर्स:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |
### getAdditive() {#getAdditive--}
```
public abstract int getAdditive()
```


वर्तमान ऐनिमेशन व्यवहार को अन्य चल रहे ऐनिमेशन्स के साथ संयोजित किया गया है या नहीं इसे दर्शाता है। पढ़ें/लिखें [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**रिटर्न:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public abstract void setAdditive(int value)
```


वर्तमान ऐनिमेशन व्यवहार को अन्य चल रहे ऐनिमेशन्स के साथ संयोजित किया गया है या नहीं इसे दर्शाता है। पढ़ें/लिखें [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**पैरामीटर्स:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |
### getProperties() {#getProperties--}
```
public abstract IBehaviorPropertyCollection getProperties()
```


व्यवहार के गुणों को दर्शाता है। केवल-पढ़ने योग्य [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**रिटर्न:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```


इफ़ेक्ट व्यवहार के लिए टाइमिंग गुणों को दर्शाता है। पढ़ें/लिखें [ITiming](../../com.aspose.slides/itiming).

**रिटर्न:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```


इफ़ेक्ट व्यवहार के लिए टाइमिंग गुणों को दर्शाता है। पढ़ें/लिखें [ITiming](../../com.aspose.slides/itiming).

**पैरामीटर्स:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |