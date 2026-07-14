---
title: GradientStopCollectionEffectiveData
second_title: Aspose.Slides Android के लिए, Java API रेफ़रेंस के माध्यम से
description: GradientStopData ऑब्जेक्ट्स का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/gradientstopcollectioneffectivedata/
---
**विरासत:**
java.lang.Object

**सभी कार्यान्वित इंटरफ़ेस:**
com.aspose.slides.IEffectiveData, [com.aspose.slides.IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)
```
public class GradientStopCollectionEffectiveData implements IEffectiveData, IGradientStopCollectionEffectiveData
```

GradientStopData ऑब्जेक्ट्स का संग्रह दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [size()](#size--) | कलेक्शन में ग्रेडिएंट स्टॉप्स की संख्या लौटाता है। |
| [get_Item(int index)](#get-Item-int-) | इंडेक्स द्वारा ग्रेडिएंट स्टॉप लौटाता है। |
| [iterator()](#iterator--) | एक इटररेटर लौटाता है जो कलेक्शन पर इटररेट करता है। |
| [iteratorJava()](#iteratorJava--) | पूरे कलेक्शन के लिए एक जावा इटरटर लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | कलेक्शन के सभी तत्वों को निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो दर्शाता है कि कलेक्शन तक पहुँच synchronized (थ्रेड-सेफ़) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | एक synchronization root लौटाता है। |
### size() {#size--}
```
public final int size()
```

कलेक्शन में ग्रेडिएंट स्टॉप्स की संख्या लौटाता है। केवल पढ़ने योग्य int।

**रिटर्न:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IGradientStopEffectiveData get_Item(int index)
```

इंडेक्स द्वारा ग्रेडिएंट स्टॉप लौटाता है।

**परिमाण:**
| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[IGradientStopEffectiveData](../../com.aspose.slides/igradientstopeffectivedata)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStopEffectiveData> iterator()
```

एक इटररेटर लौटाता है जो कलेक्शन पर इटररेट करता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStopEffectiveData> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStopEffectiveData> iteratorJava()
```

पूरा कलेक्शन के लिए एक जावा इटरटर लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStopEffectiveData> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

कलेक्शन के सभी तत्वों को निर्दिष्ट एरे में कॉपी करता है।

**परिमाण:**
| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य एरे। |
| index | int | लक्ष्य एरे में प्रारंभिक इंडेक्स। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

एक मान लौटाता है जो दर्शाता है कि कलेक्शन तक पहुँच synchronized (थ्रेड-सेफ़) है या नहीं। केवल पढ़ने योग्य boolean।

**रिटर्न:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

एक synchronization root लौटाता है। केवल पढ़ने योग्य Object।

**रिटर्न:**
java.lang.Object