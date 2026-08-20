---
title: GradientStopCollectionEffectiveData
second_title: Aspose.Slides के लिए Java API रेफ़रेंस
description: GradientStopData ऑब्जेक्ट्स का एक संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/gradientstopcollectioneffectivedata/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
com.aspose.slides.IEffectiveData, [com.aspose.slides.IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)  
```
public class GradientStopCollectionEffectiveData implements IEffectiveData, IGradientStopCollectionEffectiveData
```

एक GradientStopData ऑब्जेक्ट्स का संग्रह दर्शाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [size()](#size--) | संग्रह में ग्रेडिएंट स्टॉप की संख्या लौटाता है। |
| [get_Item(int index)](#get-Item-int-) | इंडेक्स द्वारा ग्रेडिएंट स्टॉप लौटाता है। |
| [iterator()](#iterator--) | संग्रह के माध्यम से इटरेट करने वाला एन्यूमेरेटर लौटाता है। |
| [iteratorJava()](#iteratorJava--) | पूरी संग्रह के लिए जावा इटरेटर लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | सभी तत्वों को निर्दिष्ट सरणी में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | यह दर्शाता है कि संग्रह तक पहुँच समकालिक (थ्रेड-सेफ़) है या नहीं, ऐसा मान लौटाता है। |
| [getSyncRoot()](#getSyncRoot--) | एक समकालिक मूल (सिंक्रोनाइज़ेशन रूट) लौटाता है। |

### size() {#size--}
```
public final int size()
```

संग्रह में ग्रेडिएंट स्टॉप की संख्या लौटाता है। केवल-पढ़ने योग्य int।

**वापसी:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final IGradientStopEffectiveData get_Item(int index)
```

इंडेक्स द्वारा ग्रेडिएंट स्टॉप लौटाता है।

**परामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**वापसी:**  
[IGradientStopEffectiveData](../../com.aspose.slides/igradientstopeffectivedata)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStopEffectiveData> iterator()
```

संग्रह के माध्यम से इटरेट करने वाला एन्यूमेरेटर लौटाता है।

**वापसी:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStopEffectiveData> - संग्रह के माध्यम से इटरेट करने के लिए उपयोग किया जा सकता है ऐसा IGenericEnumerator।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStopEffectiveData> iteratorJava()
```

पूरी संग्रह के लिए जावा इटरेटर लौटाता है।

**वापसी:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStopEffectiveData> - पूरी संग्रह के लिए java.util.Iterator।

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

सभी तत्वों को निर्दिष्ट सरणी में कॉपी करता है।

**परामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य सरणी। |
| index | int | लक्ष्य सरणी में प्रारम्भिक सूचकांक। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

संग्रह तक पहुँच समकालिक (थ्रेड-सेफ़) है या नहीं, दर्शाने वाला मान लौटाता है। केवल-पढ़ने योग्य boolean।

**वापसी:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

एक समकालिक मूल (सिंक्रोनाइज़ेशन रूट) लौटाता है। केवल-पढ़ने योग्य Object।

**वापसी:**  
java.lang.Object