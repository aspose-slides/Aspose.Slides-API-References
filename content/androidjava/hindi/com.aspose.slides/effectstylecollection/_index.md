---
title: EffectStyleCollection
second_title: Aspose.Slides for Android - Java API संदर्भ
description: इफ़ेक्ट शैलियों के संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/effectstylecollection/
---
**विरासत:**  
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IEffectStyleCollection](../../com.aspose.slides/ieffectstylecollection)  
```
public final class EffectStyleCollection extends DomObject<FormatScheme> implements IEffectStyleCollection
```

इफ़ेक्ट शैलियों का एक संग्रह दर्शाता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट स्थिति पर एक तत्व लौटाता है। |
| [iterator()](#iterator--) | संग्रह के माध्यम से इटरैट करने वाला एक एन्यूमरेटर लौटाता है। |
| [iteratorJava()](#iteratorJava--) | संपूर्ण संग्रह के लिए एक जावा इटरेटर लौटाता है। |
| [size()](#size--) | संग्रह में तत्वों की संख्या लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | संग्रह से सभी तत्वों को निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | यह दर्शाता है कि संग्रह तक पहुंच समक्रमित (थ्रेड-सुरक्षित) है या नहीं, इसका मान लौटाता है। |
| [getSyncRoot()](#getSyncRoot--) | समक्रमण रूट लौटाता है। |
### get_Item(int index) {#get-Item-int-}
```
public final IEffectStyle get_Item(int index)
```

निर्दिष्ट स्थिति पर एक तत्व लौटाता है। केवल-पढ़ने योग्य [EffectStyle](../../com.aspose.slides/effectstyle)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | तत्व की स्थिति। |

**रिटर्न:**  
[IEffectStyle](../../com.aspose.slides/ieffectstyle) - निर्दिष्ट स्थिति पर तत्व।

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectStyle> iterator()
```

संग्रह के माध्यम से इटरैट करने वाला एक एन्यूमरेटर लौटाता है।

**रिटर्न:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectStyle> - संग्रह के माध्यम से इटरैट करने के लिए उपयोग किया जा सकने वाला IGenericEnumerator।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectStyle> iteratorJava()
```

संपूर्ण संग्रह के लिए एक जावा इटरेटर लौटाता है।

**रिटर्न:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectStyle> - संपूर्ण संग्रह के लिए एक java.util.Iterator।

### size() {#size--}
```
public final int size()
```

संग्रह में तत्वों की संख्या लौटाता है। केवल-पढ़ने योग्य int, केवल-पढ़ने योग्य int।

**रिटर्न:**  
int

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

संग्रह से सभी तत्वों को निर्दिष्ट एरे में कॉपी करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य एरे। |
| index | int | लक्ष्य एरे में प्रारम्भिक सूचकांक। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

यह दर्शाता है कि संग्रह तक पहुंच समक्रमित (थ्रेड-सुरक्षित) है या नहीं, इसका मान लौटाता है। केवल-पढ़ने योग्य boolean।

**रिटर्न:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

समक्रमण रूट लौटाता है। केवल-पढ़ने योग्य Object।

**रिटर्न:**  
java.lang.Object