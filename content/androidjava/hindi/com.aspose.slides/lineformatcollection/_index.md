---
title: LineFormatCollection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: रेखा शैलियों के संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/lineformatcollection/
---
**विरासत:**  
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.ILineFormatCollection](../../com.aspose.slides/ilineformatcollection)  
```
public final class LineFormatCollection extends DomObject<FormatScheme> implements ILineFormatCollection
```

रेखा शैलियों के संग्रह का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमणिका पर तत्व प्राप्त करता है। |
| [iterator()](#iterator--) | कलेक्शन के माध्यम से इटररेट करने वाला enumerator लौटाता है। |
| [iteratorJava()](#iteratorJava--) | पूरे कलेक्शन के लिए एक java iterator लौटाता है। |
| [size()](#size--) | कलेक्शन में वास्तविक रूप से मौजूद तत्वों की संख्या प्राप्त करता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | कलेक्शन से सभी तत्वों को निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो बताता है कि कलेक्शन तक पहुंच synchronized (थ्रेड-सेफ़) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | एक synchronization root लौटाता है। |

### get_Item(int index) {#get-Item-int-}
```
public final ILineFormat get_Item(int index)
```

निर्दिष्ट अनुक्रमणिका पर तत्व प्राप्त करता है। Read-only [ILineFormat](../../com.aspose.slides/ilineformat).

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न वैल्यू:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ILineFormat> iterator()
```

कलेक्शन के माध्यम से इटररेट करने वाला enumerator लौटाता है।

**रिटर्न वैल्यू:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILineFormat> - एक IGenericEnumerator जो कलेक्शन के माध्यम से इटररेट करने के लिए उपयोग किया जा सकता है।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ILineFormat> iteratorJava()
```

पूरे कलेक्शन के लिए एक java iterator लौटाता है।

**रिटर्न वैल्यू:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILineFormat> - पूरे कलेक्शन के लिए एक java.util.Iterator।

### size() {#size--}
```
public final int size()
```

कलेक्शन में वास्तविक रूप से मौजूद तत्वों की संख्या प्राप्त करता है। Read-only int.

**रिटर्न वैल्यू:**  
int

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

कलेक्शन से सभी तत्वों को निर्दिष्ट एरे में कॉपी करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य एरे। |
| index | int | लक्ष्य एरे में प्रारम्भिक अनुक्रमणिका। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

एक मान लौटाता है जो बताता है कि कलेक्शन तक पहुंच synchronized (थ्रेड-सेफ़) है या नहीं। Read-only boolean.

**रिटर्न वैल्यू:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

एक synchronization root लौटाता है। Read-only Object.

**रिटर्न वैल्यू:**  
java.lang.Object