---
title: Behavior
second_title: Aspose.Slides for Android के माध्यम से Java API संदर्भ
description: इफ़ेक्ट की बेस क्लास व्यवहार को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/behavior/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior), com.aspose.slides.IDOMObject
```
public abstract class Behavior implements IBehavior, IDOMObject
```

इफ़ेक्ट के बेस क्लास व्यवहार को दर्शाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAccumulate()](#getAccumulate--) | बताता है कि क्या एनीमेशन व्यवहार संचित होते हैं। |
| [setAccumulate(byte value)](#setAccumulate-byte-) | बताता है कि क्या एनीमेशन व्यवहार संचित होते हैं। |
| [getAdditive()](#getAdditive--) | बताता है कि क्या वर्तमान एनीमेशन व्यवहार को अन्य चल रही एनीमेशन के साथ जोड़ा जाता है। |
| [setAdditive(int value)](#setAdditive-int-) | बताता है कि क्या वर्तमान एनीमेशन व्यवहार को अन्य चल रही एनीमेशन के साथ जोड़ा जाता है। |
| [getProperties()](#getProperties--) | व्यवहार की विशेषताओं को दर्शाता है। |
| [getTiming()](#getTiming--) | इफ़ेक्ट व्यवहार के समय संबंधी विशेषताओं को दर्शाता है। |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | इफ़ेक्ट व्यवहार के समय संबंधी विशेषताओं को दर्शाता है। |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Parent_Immediate वस्तु को लौटाता है। केवल-पढ़ने योग्य IDOMObject।

**वापसी:**
com.aspose.slides.IDOMObject

### getAccumulate() {#getAccumulate--}
```
public final byte getAccumulate()
```


बताता है कि क्या एनीमेशन व्यवहार संचित होते हैं। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**वापसी:**
byte

### setAccumulate(byte value) {#setAccumulate-byte-}
```
public final void setAccumulate(byte value)
```


बताता है कि क्या एनीमेशन व्यवहार संचित होते हैं। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getAdditive() {#getAdditive--}
```
public final int getAdditive()
```


बताता है कि क्या वर्तमान एनीमेशन व्यवहार को अन्य चल रही एनीमेशन के साथ जोड़ा जाता है। पढ़ने/लिखने योग्य [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype)।

**वापसी:**
int

### setAdditive(int value) {#setAdditive-int-}
```
public final void setAdditive(int value)
```


बताता है कि क्या वर्तमान एनीमेशन व्यवहार को अन्य चल रही एनीमेशन के साथ जोड़ा जाता है। पढ़ने/लिखने योग्य [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getProperties() {#getProperties--}
```
public final IBehaviorPropertyCollection getProperties()
```


व्यवहार की विशेषताओं को दर्शाता है। केवल-पढ़ने योग्य [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)।

**वापसी:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)

### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```


इफ़ेक्ट व्यवहार के समय संबंधी विशेषताओं को दर्शाता है। पढ़ने/लिखने योग्य [ITiming](../../com.aspose.slides/itiming)।

**वापसी:**
[ITiming](../../com.aspose.slides/itiming)

### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```


इफ़ेक्ट व्यवहार के समय संबंधी विशेषताओं को दर्शाता है। पढ़ने/लिखने योग्य [ITiming](../../com.aspose.slides/itiming)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |