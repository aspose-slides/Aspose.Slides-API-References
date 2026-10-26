---
title: Behavior
second_title: Aspose.Slides for Java API संदर्भ
description: इफ़ेक्ट की बेस क्लास व्यवहार को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/behavior/
---
**Inheritance:**  
विरासत: java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior), com.aspose.slides.IDOMObject  
```
public abstract class Behavior implements IBehavior, IDOMObject
```

इफ़ेक्ट के बेस क्लास व्यवहार को प्रदर्शित करता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAccumulate()](#getAccumulate--) | निर्धारित करता है कि क्या एनीमेशन व्यवहार संचित होते हैं। |
| [setAccumulate(byte value)](#setAccumulate-byte-) | निर्धारित करता है कि क्या एनीमेशन व्यवहार संचित होते हैं। |
| [getAdditive()](#getAdditive--) | निर्धारित करता है कि क्या वर्तमान एनीमेशन व्यवहार को अन्य चल रहे एनीमेशन के साथ मिलाया जाता है। |
| [setAdditive(int value)](#setAdditive-int-) | निर्धारित करता है कि क्या वर्तमान एनीमेशन व्यवहार को अन्य चल रहे एनीमेशन के साथ मिलाया जाता है। |
| [getProperties()](#getProperties--) | व्यवहार की गुणधर्मों को दर्शाता है। |
| [getTiming()](#getTiming--) | इफ़ेक्ट व्यवहार के समय गुणधर्मों को दर्शाता है। |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | इफ़ेक्ट व्यवहार के समय गुणधर्मों को दर्शाता है। |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य IDOMObject.

**रिटर्न:**  
com.aspose.slides.IDOMObject

### getAccumulate() {#getAccumulate--}
```
public final byte getAccumulate()
```

निर्धारित करता है कि क्या एनीमेशन व्यवहार संचित होते हैं। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**रिटर्न:**  
byte

### setAccumulate(byte value) {#setAccumulate-byte-}
```
public final void setAccumulate(byte value)
```

निर्धारित करता है कि क्या एनीमेशन व्यवहार संचित होते हैं। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getAdditive() {#getAdditive--}
```
public final int getAdditive()
```

निर्धारित करता है कि क्या वर्तमान एनीमेशन व्यवहार को अन्य चल रहे एनीमेशन के साथ मिलाया जाता है। पढ़ने/लिखने योग्य [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype)।

**रिटर्न:**  
int

### setAdditive(int value) {#setAdditive-int-}
```
public final void setAdditive(int value)
```

निर्धारित करता है कि क्या वर्तमान एनीमेशन व्यवहार को अन्य चल रहे एनीमेशन के साथ मिलाया जाता है। पढ़ने/लिखने योग्य [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getProperties() {#getProperties--}
```
public final IBehaviorPropertyCollection getProperties()
```

व्यवहार की गुणधर्मों को दर्शाता है। केवल पढ़ने योग्य [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)।

**रिटर्न:**  
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)

### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```

इफ़ेक्ट व्यवहार के समय गुणधर्मों को दर्शाता है। पढ़ने/लिखने योग्य [ITiming](../../com.aspose.slides/itiming)।

**रिटर्न:**  
[ITiming](../../com.aspose.slides/itiming)

### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```

इफ़ेक्ट व्यवहार के समय गुणधर्मों को दर्शाता है। पढ़ने/लिखने योग्य [ITiming](../../com.aspose.slides/itiming)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |