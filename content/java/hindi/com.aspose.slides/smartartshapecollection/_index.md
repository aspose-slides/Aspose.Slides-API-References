---
title: SmartArtShapeCollection
second_title: Aspose.Slides for Java API संदर्भ
description: SmartArt आकारों के संग्रह का प्रतिनिधित्व करता है
type: docs
url: /hi/com.aspose.slides/smartartshapecollection/
---
**विरासत:**  
java.lang.Object

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)  
```
public class SmartArtShapeCollection implements ISmartArtShapeCollection
```

एक SmartArt आकारों का संग्रह प्रस्तुत करता है  
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [size()](#size--) | कलेक्सन में वास्तव में सम्मिलित तत्वों की संख्या प्राप्त करता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है। |
| [isSynchronized()](#isSynchronized--) | यह दर्शाने वाला मान लौटाता है कि कलेक्सन तक पहुँच समकालीन (थ्रेड-सेफ़) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | एक समकालीन रूट लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | सभी तत्वों को कलेक्सन से निर्दिष्ट एरे में कॉपी करता है। |
| [iterator()](#iterator--) | कलेक्सन के माध्यम से इटरैट करने वाला एनोमरेटर लौटाता है। |
| [iteratorJava()](#iteratorJava--) | पूरे कलेक्सन के लिए एक java इटरैटर लौटाता है। |
### size() {#size--}
```
public final int size()
```

कलेक्सन में वास्तव में सम्मिलित तत्वों की संख्या प्राप्त करता है। केवल-पढ़ने योग्य int।

**वापसी:**  
int
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtShape get_Item(int index)
```

निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है। केवल-पढ़ने योग्य [SmartArtShape](../../com.aspose.slides/smartartshape)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | आकार का इंडेक्स |

**वापसी:**  
[ISmartArtShape](../../com.aspose.slides/ismartartshape) - SmartArt आकार
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

कलेक्सन तक पहुँच समकालीन (थ्रेड-सेफ़) है या नहीं, यह दर्शाने वाला मान लौटाता है। केवल-पढ़ने योग्य boolean।

**वापसी:**  
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

एक समकालीन रूट लौटाता है। केवल-पढ़ने योग्य Object।

**वापसी:**  
java.lang.Object
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

सभी तत्वों को कलेक्सन से निर्दिष्ट एरे में कॉपी करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य एरे। |
| index | int | लक्ष्य एरे में प्रारंभिक इंडेक्स। |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtShape> iterator()
```

कलेक्सन के माध्यम से इटरैट करने वाला एनोमरेटर लौटाता है।

**वापसी:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtShape> - कलेक्सन के माध्यम से इटरैट करने के लिए उपयोग किया जा सकने वाला IGenericEnumerator।
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtShape> iteratorJava()
```

पूरे कलेक्सन के लिए एक java इटरैटर लौटाता है।

**वापसी:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtShape> - पूरे कलेक्सन के लिए एक java.util.Iterator।