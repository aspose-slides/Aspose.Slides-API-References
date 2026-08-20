---
title: SmartArtNodeCollection
second_title: जावा के लिए Aspose.Slides API संदर्भ
description: SmartArt नोड्स का एक संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/smartartnodecollection/
---
**विरासत:**
java.lang.Object

**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
```
public final class SmartArtNodeCollection implements ISmartArtNodeCollection
```

SmartArt नोड्स का एक संग्रह दर्शाता है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | इंडेक्स द्वारा नोड लौटाता है |
| [size()](#size--) | क्लैक्शन में नोड्स की गिनती लौटाता है Read-only  int  Read-only  int . |
| [addNode()](#addNode--) | नया smart art नोड या उप-नोड जोड़ता है। |
| [removeNode(int index)](#removeNode-int-) | इंडेक्स द्वारा नोड या उप-नोड हटाता है |
| [removeNode(ISmartArtNode node)](#removeNode-com.aspose.slides.ISmartArtNode-) | नोड या उप-नोड हटाता है |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | नोड्स क्लैक्शन में चयनित स्थिति में नया नोड जोड़ता है |
| [iterator()](#iterator--) | क्लैक्शन के माध्यम से इटरैट करने वाला एन्यूमरेटर लौटाता है। |
| [iteratorJava()](#iteratorJava--) | सम्पूर्ण क्लैक्शन के लिए java इटरेटर लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | क्लैक्शन से सभी तत्व निर्दिष्ट ऐरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | क्लैक्शन तक पहुँच समक्रमित (थ्रेड-सेफ़) है या नहीं दर्शाने वाला मान लौटाता है। |
| [getSyncRoot()](#getSyncRoot--) | समक्रमण रूट लौटाता है। |
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtNode get_Item(int index)
```


इंडेक्स द्वारा नोड लौटाता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | तत्व का शून्य-आधारित इंडेक्स |

**रिटर्न:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - SmartArt नोड
### size() {#size--}
```
public final int size()
```


क्लैक्शन में नोड्स की गिनती लौटाता है Read-only  int  Read-only  int .

**रिटर्न:**
int
### addNode() {#addNode--}
```
public final ISmartArtNode addNode()
```


नया smart art नोड या उप-नोड जोड़ता है।

**रिटर्न:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - जोड़ा गया नोड
### removeNode(int index) {#removeNode-int-}
```
public final void removeNode(int index)
```


इंडेक्स द्वारा नोड या उप-नोड हटाता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | नोड का शून्य-आधारित इंडेक्स |
### removeNode(ISmartArtNode node) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public final void removeNode(ISmartArtNode node)
```


नोड या उप-नोड हटाता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| node | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | हटाने के लिए नोड |
### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public final ISmartArtNode addNodeByPosition(int position)
```


नोड्स क्लैक्शन में चयनित स्थिति में नया नोड जोड़ता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | int | नोड की शून्य-आधारित स्थिति |

**रिटर्न:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - जोड़ा गया नोड
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iterator()
```


क्लैक्शन के माध्यम से इटरैट करने वाला एन्यूमरेटर लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iteratorJava()
```


सम्पूर्ण क्लैक्शन के लिए java इटरेटर लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


क्लैक्शन से सभी तत्व निर्दिष्ट ऐरे में कॉपी करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य ऐरे। |
| index | int | लक्ष्य ऐरे में प्रारंभिक इंडेक्स। |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


क्लैक्शन तक पहुँच समक्रमित (थ्रेड-सेफ़) है या नहीं दर्शाने वाला मान लौटाता है Read-only boolean .

**रिटर्न:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


समक्रमण रूट लौटाता है Read-only Object.

**रिटर्न:**
java.lang.Object