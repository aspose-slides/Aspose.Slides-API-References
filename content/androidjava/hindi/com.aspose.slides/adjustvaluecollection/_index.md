---
title: AdjustValueCollection
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: आकृतियों के समायोजनों का एक संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/adjustvaluecollection/
---
**विरासत:**
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
```
public final class AdjustValueCollection extends DomObject<GeometryShape> implements IAdjustValueCollection
```

आकृति के समायोजन का एक संग्रह दर्शाता है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [size()](#size--) | समायोजनों की संख्या लौटाता है। |
| [get_Item(int index)](#get-Item-int-) | इंडेक्स द्वारा समायोजन लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | संग्रह से सभी तत्व निर्दिष्ट ऐरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुँच समन्वित (थ्रेड-सेफ़) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | समन्वयन रूट लौटाता है। |
| [iterator()](#iterator--) | पूरे संग्रह के लिए एक एनेुमरेटर लौटाता है। |
### size() {#size--}
```
public final int size()
```


समायोजनों की संख्या लौटाता है। केवल-पढ़ने योग्य int।

**वापसी:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IAdjustValue get_Item(int index)
```


इंडेक्स द्वारा समायोजन लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | समायोजन का इंडेक्स। |

**वापसी:**
[IAdjustValue](../../com.aspose.slides/iadjustvalue) - [AdjustValue](../../com.aspose.slides/adjustvalue).
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


संग्रह से सभी तत्व निर्दिष्ट ऐरे में कॉपी करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य ऐरे। |
| index | int | लक्ष्य ऐरे में प्रारंभिक इंडेक्स। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुँच समन्वित (थ्रेड-सेफ़) है या नहीं। केवल-पढ़ने योग्य boolean।

**वापसी:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


समन्वयन रूट लौटाता है। केवल-पढ़ने योग्य Object।

**वापसी:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.IEnumerator iterator()
```


पूरे संग्रह के लिए एक एनेुमरेटर लौटाता है।

**वापसी:**
com.aspose.ms.System.Collections.IEnumerator