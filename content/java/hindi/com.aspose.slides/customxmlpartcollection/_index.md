---
title: CustomXmlPartCollection
second_title: Aspose.Slides for Java API संदर्भ
description: कस्टम XML भागों का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/customxmlpartcollection/
---
**विरासत:**
java.lang.Object

**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.ICustomXmlPartCollection](../../com.aspose.slides/icustomxmlpartcollection), com.aspose.slides.IDOMObject
```
public class CustomXmlPartCollection implements ICustomXmlPartCollection, IDOMObject
```

कस्टम XML भागों का संग्रह दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट सूचकांक पर तत्व लौटाता है। |
| [size()](#size--) | संग्रह में कस्टम XML भागों की गणना लौटाता है। |
| [add(String xmlString)](#add-java.lang.String-) | नया कस्टम XML भाग जोड़ता है। |
| [add(byte[] xmlData)](#add-byte---) | नया कस्टम XML भाग जोड़ता है। |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | नया कस्टम XML भाग जोड़ता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट सूचकांक पर कस्टम XML भाग हटाता है। |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | संग्रह से विशिष्ट वस्तु की पहली उपस्थिति हटाता है। |
| [clear()](#clear--) | संग्रह से सभी आइटम हटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | यह दर्शाने वाला मान लौटाता है कि क्या संग्रह तक पहुंच समकालिक (थ्रेड-सुरक्षित) है। |
| [getSyncRoot()](#getSyncRoot--) | एक समकालिक मूल लौटाता है। |
| [iterator()](#iterator--) | वह इटेरेटर लौटाता है जो संग्रह के माध्यम से इटरिट करता है। |
| [iteratorJava()](#iteratorJava--) | पूरी संग्रह के लिए एक जावा इटेरेटर लौटाता है। |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### get_Item(int index) {#get-Item-int-}
```
public final ICustomXmlPart get_Item(int index)
```

निर्दिष्ट सूचकांक पर तत्व लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | प्राप्त करने वाले तत्व का शून्य-आधारित सूचकांक। |

**रिटर्न:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - निर्दिष्ट सूचकांक पर तत्व।

### size() {#size--}
```
public final int size()
```

संग्रह में कस्टम XML भागों की गणना लौटाता है। केवल-पढ़ने योग्य int।

**रिटर्न:**
int

### add(String xmlString) {#add-java.lang.String-}
```
public final ICustomXmlPart add(String xmlString)
```

नया कस्टम XML भाग जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xmlString | java.lang.String | जोड़े जाने वाले नए भाग की XML स्ट्रिंग। |

**रिटर्न:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - निर्मित कस्टम XML भाग।

### add(byte[] xmlData) {#add-byte---}
```
public final ICustomXmlPart add(byte[] xmlData)
```

नया कस्टम XML भाग जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xmlData | byte[] | जोड़े जाने वाले नए भाग का XML डेटा। |

**रिटर्न:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - निर्मित कस्टम XML भाग।

### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public final ICustomXmlPart add(InputStream inputStream)
```

नया कस्टम XML भाग जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| inputStream | java.io.InputStream | जोड़े जाने वाले नए भाग का XML डेटा इनपुटस्ट्रीम। |

**रिटर्न:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - निर्मित कस्टम XML भाग।

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

निर्दिष्ट सूचकांक पर कस्टम XML भाग हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाए जाने वाले तत्व का शून्य-आधारित सूचकांक। |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public final boolean remove(ICustomXmlPart item)
```

संग्रह से विशिष्ट वस्तु की पहली उपस्थिति हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | हटाए जाने वाला कस्टम XML भाग। |

**रिटर्न:**
boolean - true यदि आइटम सफलतापूर्वक हटाया गया; अन्यथा false।

### clear() {#clear--}
```
public final void clear()
```

संग्रह से सभी आइटम हटाता है।

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

निर्दिष्ट एरे में कॉपी करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | जिस एरे में कॉपी करना है। |
| index | int | कॉपी शुरू करने का सूचकांक। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

यह दर्शाने वाला मान लौटाता है कि क्या संग्रह तक पहुंच समकालिक (थ्रेड-सुरक्षित) है। केवल-पढ़ने योग्य boolean।

**रिटर्न:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

एक समकालिक मूल लौटाता है। केवल-पढ़ने योग्य Object।

**रिटर्न:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iterator()
```

संग्रह के माध्यम से इटरिट करने वाला इटेरेटर लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - एक IGenericEnumerator जो संग्रह के माध्यम से इटरिट किया जा सकता है।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iteratorJava()
```

पूरी संग्रह के लिए जावा इटेरेटर लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - पूरी संग्रह के लिए एक java.util.Iterator।

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य IDOMObject।

**रिटर्न:**
com.aspose.slides.IDOMObject