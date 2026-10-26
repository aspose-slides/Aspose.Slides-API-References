---
title: SmartArtNodeCollection
second_title: Aspose.Slides Android के लिए Java API संदर्भ
description: SmartArt नोड्स का एक संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/smartartnodecollection/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)  
```
public final class SmartArtNodeCollection implements ISmartArtNodeCollection
```

SmartArt नोड्स का एक संग्रह दर्शाता है।

## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | सूचकांक द्वारा नोड लौटाता है |
| [size()](#size--) | संग्रह में नोड्स की गिनती लौटाता है केवल- पढ़ने योग्य int केवल- पढ़ने योग्य int . |
| [addNode()](#addNode--) | नया स्मार्ट आर्ट नोड या उप-नोड जोड़ें। |
| [removeNode(int index)](#removeNode-int-) | सूचकांक द्वारा नोड या उप-नोड हटाएँ |
| [removeNode(ISmartArtNode node)](#removeNode-com.aspose.slides.ISmartArtNode-) | नोड या उप-नोड हटाएँ |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | चयनित स्थिति में नोड संग्रह में नया नोड जोड़ें |
| [iterator()](#iterator--) | संग्रह के माध्यम से इटररेट करने वाला एन्यूमरेटर लौटाता है। |
| [iteratorJava()](#iteratorJava--) | पूरी संग्रह के लिए जावा इटररेटर लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | संग्रह से सभी तत्व निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | यह दर्शाने वाला मान लौटाता है कि संग्रह तक पहुँच सिंक्रनाइज़ है (थ्रेड-सेफ़) या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | एक सिंक्रनाइज़ेशन रूट लौटाता है। |

### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtNode get_Item(int index)
```

सूचकांक द्वारा नोड लौटाता है

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | तत्व का शून्य-आधारित सूचकांक |

**Returns:**  
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - SmartArt नोड

### size() {#size--}
```
public final int size()
```

संग्रह में नोड्स की गिनती लौटाता है केवल- पढ़ने योग्य int केवल- पढ़ने योग्य int .

**Returns:**  
int

### addNode() {#addNode--}
```
public final ISmartArtNode addNode()
```

नया स्मार्ट आर्ट नोड या उप-नोड जोड़ें।

**Returns:**  
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - जोड़ा गया नोड

### removeNode(int index) {#removeNode-int-}
```
public final void removeNode(int index)
```

सूचकांक द्वारा नोड या उप-नोड हटाएँ

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | नोड का शून्य-आधारित सूचकांक |

### removeNode(ISmartArtNode node) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public final void removeNode(ISmartArtNode node)
```

नोड या उप-नोड हटाएँ

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| node | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | हटाने के लिए नोड |

### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public final ISmartArtNode addNodeByPosition(int position)
```

चयनित स्थिति में नोड संग्रह में नया नोड जोड़ें

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| position | int | शून्य-आधारित नोड स्थिति |

**Returns:**  
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - जोड़ा गया नोड

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iterator()
```

संग्रह के माध्यम से इटररेट करने वाला एन्यूमरेटर लौटाता है।

**Returns:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - संग्रह के माध्यम से इटररेट करने के लिए उपयोग किया जाने वाला IGenericEnumerator।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iteratorJava()
```

पूरी संग्रह के लिए जावा इटररेटर लौटाता है।

**Returns:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - पूरी संग्रह के लिए एक java.util.Iterator।

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

संग्रह से सभी तत्व निर्दिष्ट एरे में कॉपी करता है।

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य एरे। |
| index | int | लक्ष्य एरे में प्रारंभिक सूचकांक। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

यह दर्शाने वाला मान लौटाता है कि संग्रह तक पहुँच सिंक्रनाइज़ है (थ्रेड-सेफ़) या नहीं। केवल- पढ़ने योग्य boolean .

**Returns:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

एक सिंक्रनाइज़ेशन रूट लौटाता है। केवल- पढ़ने योग्य Object।

**Returns:**  
java.lang.Object