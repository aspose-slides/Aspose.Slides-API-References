---
title: CustomXmlPartCollection
second_title: जावा API रेफरेंस के जरिए Android के लिए Aspose.Slides
description: कस्टम XML भागों का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/customxmlpartcollection/
---
**विरासत:** java.lang.Object

**सभी लागू इंटरफ़ेस:** [com.aspose.slides.ICustomXmlPartCollection](../../com.aspose.slides/icustomxmlpartcollection), com.aspose.slides.IDOMObject ```
public class CustomXmlPartCollection implements ICustomXmlPartCollection, IDOMObject
```

कस्टम xml भागों का संग्रह दर्शाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमणिका पर तत्व लौटाता है। |
| [size()](#size--) | संग्रह में कस्टम xml भागों की गिनती लौटाता है। |
| [add(String xmlString)](#add-java.lang.String-) | नया कस्टम xml भाग जोड़ता है। |
| [add(byte[] xmlData)](#add-byte---) | नया कस्टम xml भाग जोड़ता है। |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | नया कस्टम xml भाग जोड़ता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट अनुक्रमणिका पर कस्टम xml भाग हटाता है। |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | संग्रह से एक विशिष्ट वस्तु की पहली उपस्थिति हटाता है। |
| [clear()](#clear--) | संग्रह से सभी आइटम हटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो संकेत करता है कि संग्रह तक पहुँच सिंक्रनाइज़्ड (थ्रेड-सुरक्षित) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | एक सिंक्रनाइज़ेशन रूट लौटाता है। |
| [iterator()](#iterator--) | एक एनेमरेटर लौटाता है जो संग्रह के माध्यम से इटरनेट करता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए जावा इटररेटर लौटाता है। |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### get_Item(int index) {#get-Item-int-}
```
public final ICustomXmlPart get_Item(int index)
```

निर्दिष्ट अनुक्रमणिका पर तत्व लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | तत्व प्राप्त करने के लिए शून्य-आधारित अनुक्रमणिका। |

**वापसी:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - निर्दिष्ट अनुक्रमणिका पर तत्व।

### size() {#size--}
```
public final int size()
```

संग्रह में कस्टम xml भागों की गिनती लौटाता है। केवल-पढ़ने योग्य int।

**वापसी:**
int

### add(String xmlString) {#add-java.lang.String-}
```
public final ICustomXmlPart add(String xmlString)
```

नया कस्टम xml भाग जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xmlString | java.lang.String | जोड़ने वाले नए भाग की xml स्ट्रिंग। |

**वापसी:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - बनाए गए कस्टम xml भाग।

### add(byte[] xmlData) {#add-byte---}
```
public final ICustomXmlPart add(byte[] xmlData)
```

नया कस्टम xml भाग जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xmlData | byte[] | जोड़ने वाले नए भाग का xml डेटा। |

**वापसी:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - बनाए गए कस्टम xml भाग।

### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public final ICustomXmlPart add(InputStream inputStream)
```

नया कस्टम xml भाग जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| inputStream | java.io.InputStream | जोड़ने वाले नए भाग के xml डेटा वाला inputStream। |

**वापसी:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - बनाए गए कस्टम xml भाग।

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

निर्दिष्ट अनुक्रमणिका पर कस्टम xml भाग हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने वाले तत्व की शून्य-आधारित अनुक्रमणिका। |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public final boolean remove(ICustomXmlPart item)
```

संग्रह से एक विशिष्ट वस्तु की पहली उपस्थिति हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | हटाने वाला कस्टम xml भाग। |

**वापसी:**
boolean - यदि आइटम सफलतापूर्वक हटाया गया तो true; अन्यथा false।

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
| array | com.aspose.ms.System.Array | कॉपी करने के लिए एरे। |
| index | int | कॉपी शुरू करने के लिए अनुक्रमणिका। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

एक मान लौटाता है जो संकेत करता है कि संग्रह तक पहुँच सिंक्रनाइज़्ड (थ्रेड-सुरक्षित) है या नहीं। केवल-पढ़ने योग्य boolean।

**वापसी:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

एक सिंक्रनाइज़ेशन रूट लौटाता है। केवल-पढ़ने योग्य Object।

**वापसी:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iterator()
```

एक एनेमरेटर लौटाता है जो संग्रह के माध्यम से इटरनेट करता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - एक IGenericEnumerator जो संग्रह के माध्यम से इटरनेट करने के लिए उपयोग किया जा सकता है।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iteratorJava()
```

पूरे संग्रह के लिए जावा इटररेटर लौटाता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - पूरे संग्रह के लिए एक java.util.Iterator।

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य IDOMObject।

**वापसी:**
com.aspose.slides.IDOMObject