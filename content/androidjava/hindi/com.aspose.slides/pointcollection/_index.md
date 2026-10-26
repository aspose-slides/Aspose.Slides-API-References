---
title: PointCollection
second_title: Aspose.Slides for Android जावा API रेफ़रेंस के माध्यम से
description: एनीमेशन बिंदुओं का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/pointcollection/
---
**विरासत:**
java.lang.Object

**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.IPointCollection](../../com.aspose.slides/ipointcollection)
```
public class PointCollection implements IPointCollection
```

एनीमेशन बिंदुओं के संग्रह का प्रतिनिधित्व करता है।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [PointCollection()](#PointCollection--) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getCount()](#getCount--) | संग्रह में बिंदुओं की संख्या लौटाता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट सूचकांक पर एक बिंदु लौटाता है। |
| [iterator()](#iterator--) | संग्रह के माध्यम से इटरट करने वाला enumerator लौटाता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए एक java iterator लौटाता है। |
### PointCollection() {#PointCollection--}
```
public PointCollection()
```


### getCount() {#getCount--}
```
public final int getCount()
```


संग्रह में बिंदुओं की संख्या लौटाता है। केवल पढ़ने योग्य int।

**वापसी:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IPoint get_Item(int index)
```


निर्दिष्ट सूचकांक पर एक बिंदु लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | तत्व का सूचकांक। |

**वापसी:**
[IPoint](../../com.aspose.slides/ipoint) - The [IPoint](../../com.aspose.slides/ipoint) object.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iterator()
```


संग्रह के माध्यम से इटरट करने वाला enumerator लौटाता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iteratorJava()
```


पूरे संग्रह के लिए एक java iterator लौटाता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - An java.util.Iterator for the entire collection.