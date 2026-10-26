---
title: EffectStyleCollection
second_title: Aspose.Slides जावा के लिए API संदर्भ
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

इफ़ेक्ट शैलियों का संग्रह दर्शाता है।

## विधियाँ

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट स्थिति पर तत्व लौटाता है। |
| [iterator()](#iterator--) | एक एनेमरेटर लौटाता है जो संग्रह के माध्यम से पुनरावृति करता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए एक जावा इटररेटर लौटाता है। |
| [size()](#size--) | संग्रह में तत्वों की संख्या लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | सभी तत्वों को संग्रह से निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुँच सिंक्रनाइज़्ड (थ्रेड-सेफ) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | एक सिंक्रनाइज़ेशन रूट लौटाता है। |

### get_Item(int index) {#get-Item-int-}
```
public final IEffectStyle get_Item(int index)
```

निर्दिष्ट स्थिति पर तत्व लौटाता है। केवल-पढ़ने-योग्य [EffectStyle](../../com.aspose.slides/effectstyle)।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | तत्व की स्थिति। |

**वापसी:**  
[IEffectStyle](../../com.aspose.slides/ieffectstyle) - निर्दिष्ट स्थिति पर तत्व।

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectStyle> iterator()
```

एक एनेमरेटर लौटाता है जो संग्रह के माध्यम से पुनरावृति करता है।

**रिटर्न वैल्यू:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectStyle> - एक IGenericEnumerator जो संग्रह के माध्यम से इटरैट करने के लिए उपयोग किया जा सकता है।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectStyle> iteratorJava()
```

पूरे संग्रह के लिए एक जावा इटररेटर लौटाता है।

**रिटर्न वैल्यू:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectStyle> - एक java.util.Iterator पूरे संग्रह के लिए।

### size() {#size--}
```
public final int size()
```

संग्रह में तत्वों की संख्या लौटाता है। केवल-पढ़ने-योग्य int, केवल-पढ़ने-योग्य int।

**रिटर्न वैल्यू:**  
int

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

सभी तत्वों को संग्रह से निर्दिष्ट एरे में कॉपी करता है।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य एरे। |
| index | int | लक्ष्य एरे में प्रारंभिक इंडेक्स। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुँच सिंक्रनाइज़्ड (थ्रेड-सेफ) है या नहीं। केवल-पढ़ने-योग्य boolean।

**रिटर्न वैल्यू:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

एक सिंक्रनाइज़ेशन रूट लौटाता है। केवल-पढ़ने-योग्य Object।

**रिटर्न वैल्यू:**  
java.lang.Object