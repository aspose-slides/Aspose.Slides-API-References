---
title: PointCollection
second_title: Aspose.Slides for Java API संदर्भ
description: एनिमेशन बिंदुओं के संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/pointcollection/
---
**विरासत:**
java.lang.Object

**सभी लागू किए गए इंटरफ़ेस:**
[com.aspose.slides.IPointCollection](../../com.aspose.slides/ipointcollection)
```
public class PointCollection implements IPointCollection
```

एनिमेशन बिंदुओं का संग्रह प्रस्तुत करता है।
## कन्स्ट्रक्टर

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [PointCollection()](#PointCollection--) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getCount()](#getCount--) | संग्रह में बिंदुओं की संख्या लौटाता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट इंडेक्स पर बिंदु लौटाता है। |
| [iterator()](#iterator--) | संग्रह के माध्यम से इटररेट करने वाला एनेुमरेटर लौटाता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए जावा इटररेटर लौटाता है। |
### PointCollection() {#PointCollection--}
```
public PointCollection()
```

### getCount() {#getCount--}
```
public final int getCount()
```

संग्रह में बिंदुओं की संख्या लौटाता है। केवल-पढ़ने योग्य int.

**रिटर्न:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IPoint get_Item(int index)
```

निर्दिष्ट इंडेक्स पर बिंदु लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | तत्व का इंडेक्स। |

**रिटर्न:**
[IPoint](../../com.aspose.slides/ipoint) - यह [IPoint](../../com.aspose.slides/ipoint) ऑब्जेक्ट।
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iterator()
```

संग्रह के माध्यम से इटररेट करने वाला एनेुमरेटर लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - एक IGenericEnumerator जिसे संग्रह के माध्यम से इटररेट करने के लिए इस्तेमाल किया जा सकता है।
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iteratorJava()
```

पूरे संग्रह के लिए जावा इटररेटर लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - एक java.util.Iterator पूरे संग्रह के लिए।