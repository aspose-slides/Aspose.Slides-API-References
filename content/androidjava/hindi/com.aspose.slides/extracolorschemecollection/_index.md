---
title: ExtraColorSchemeCollection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ के माध्यम से
description: अतिरिक्त रंग योजनाओं के संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/extracolorschemecollection/
---
**विरासत:**  
java.lang.Object

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection), com.aspose.slides.IDOMObject  
```
public class ExtraColorSchemeCollection implements IExtraColorSchemeCollection, IDOMObject
```

अतिरिक्त रंग योजनाओं का एक संग्रह दर्शाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [size()](#size--) | संग्रह में तत्वों की संख्या लौटाता है। |
| [get_Item(int index)](#get-Item-int-) | इंडेक्स द्वारा एक रंग योजना लौटाता है। |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [iterator()](#iterator--) | संग्रह के माध्यम से इटररेट करने वाला एनीमुरेटर लौटाता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए एक जावा इटररेटर लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | सभी तत्वों को निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | यह बताता है कि ArrayList तक पहुँच समन्वित (थ्रेड-सुरक्षित) है या नहीं, इसका मान लौटाता है। |
| [getSyncRoot()](#getSyncRoot--) | एक ऑब्जेक्ट लौटाता है जिसका उपयोग संग्रह तक पहुँच को समन्वित करने के लिए किया जा सकता है। |

### size() {#size--}
```
public final int size()
```

संग्रह में तत्वों की संख्या लौटाता है। केवल- पढ़ने योग्य int.

**वापसी:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final IExtraColorScheme get_Item(int index)
```

इंडेक्स द्वारा एक रंग योजना लौटाता है। केवल- पढ़ने योग्य [ExtraColorScheme](../../com.aspose.slides/extracolorscheme).

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**वापसी:**  
[IExtraColorScheme](../../com.aspose.slides/iextracolorscheme)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल- पढ़ने योग्य IDOMObject.

**वापसी:**  
com.aspose.slides.IDOMObject

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iterator()
```

संग्रह के माध्यम से इटररेट करने वाला एनीमुरेटर लौटाता है।

**वापसी:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - एक IGenericEnumerator जिसका उपयोग संग्रह के माध्यम से इटररेट करने के लिए किया जा सकता है।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iteratorJava()
```

पूरे संग्रह के लिए एक जावा इटररेटर लौटाता है।

**वापसी:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - एक java.util.Iterator पूरे संग्रह के लिए।

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

सभी तत्वों को निर्दिष्ट एरे में कॉपी करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य एरे। |
| index | int | एरे में प्रारंभिक इंडेक्स। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

यह बताता है कि ArrayList तक पहुँच समन्वित (थ्रेड-सुरक्षित) है या नहीं, इसका मान लौटाता है। केवल- पढ़ने योग्य boolean।

**वापसी:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

एक ऑब्जेक्ट लौटाता है जिसका उपयोग संग्रह तक पहुँच को समन्वित करने के लिए किया जा सकता है। केवल- पढ़ने योग्य Object.

एक समन्वयन रूट लौटाता है। केवल- पढ़ने योग्य Object।

**वापसी:**  
java.lang.Object