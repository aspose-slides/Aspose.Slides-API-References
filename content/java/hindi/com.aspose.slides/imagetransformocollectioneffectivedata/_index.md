---
title: ImageTransformOCollectionEffectiveData
second_title: Aspose.Slides for Java API संदर्भ
description: एक अपरिवर्तनीय ऑब्जेक्ट जो प्रभावी छवि ट्रांसफ़ॉर्म इफ़ेक्ट्स का केवल-पढ़ने-योग्य संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/imagetransformocollectioneffectivedata/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
com.aspose.slides.IEffectiveData, [com.aspose.slides.IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)
```
public class ImageTransformOCollectionEffectiveData implements IEffectiveData, IImageTransformOCollectionEffectiveData
```

अपरिवर्तनीय ऑब्जेक्ट जो प्रभावी छवि ट्रांसफ़ॉर्म इफ़ेक्ट्स का केवल-पढ़ने-योग्य संग्रह दर्शाता है।

--------------------

नाम IImageTransformOperationCollectionEffectiveData को IImageTransformOCollectionEffectiveData में छोटा किया गया क्योंकि COM नामों की लंबाई 39 से अधिक नहीं हो सकती।

## Constructors

| Constructor | Description |
| --- | --- |
| [ImageTransformOCollectionEffectiveData()](#ImageTransformOCollectionEffectiveData--) |  |

## Methods

| Method | Description |
| --- | --- |
| [size()](#size--) | संग्रह में छवि प्रभावों की संख्या लौटाता है। |
| [get_Item(int index)](#get-Item-int-) | सूचकांक द्वारा तत्व लौटाता है। |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि निर्दिष्ट ऑब्जेक्ट वर्तमान ऑब्जेक्ट के समान है या नहीं। |
| [hashCode()](#hashCode--) | किसी विशेष प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है, जो हैशिंग एल्गोरिदम और हैश टेबल जैसी डेटा संरचनाओं में उपयोग के लिए उपयुक्त है। |
| [iterator()](#iterator--) | एक इटेरेटर लौटाता है जो संग्रह के माध्यम से इटरेट करता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए एक जावा इटेरेटर लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | सभी तत्वों को संग्रह से निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | यह दर्शाता है कि संग्रह तक पहुंच सिंक्रनाइज़्ड (थ्रेड-सुरक्षित) है या नहीं, इसका मान लौटाता है। |
| [getSyncRoot()](#getSyncRoot--) | एक सिंक्रनाइज़ेशन रूट लौटाता है। |
### ImageTransformOCollectionEffectiveData() {#ImageTransformOCollectionEffectiveData--}
```
public ImageTransformOCollectionEffectiveData()
```

### size() {#size--}
```
public final int size()
```

संग्रह में छवि प्रभावों की संख्या लौटाता है। केवल-पढ़ने-योग्य int।

**Returns:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IEffectEffectiveData get_Item(int index)
```

सूचकांक द्वारा तत्व लौटाता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | तत्व का सूचकांक। |

**Returns:**
[IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata) - [IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata) ऑब्जेक्ट।

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

निर्धारित करता है कि निर्दिष्ट ऑब्जेक्ट वर्तमान ऑब्जेक्ट के समान है या नहीं।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | वर्तमान ऑब्जेक्ट के साथ तुलना करने के लिए ऑब्जेक्ट। |

**Returns:**
boolean - यदि निर्दिष्ट ऑब्जेक्ट वर्तमान ऑब्जेक्ट के बराबर है तो true; अन्यथा false।

### hashCode() {#hashCode--}
```
public int hashCode()
```

किसी विशेष प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है, जो हैशिंग एल्गोरिदम और हैश टेबल जैसी डेटा संरचनाओं में उपयोग के लिए उपयुक्त है।

**Returns:**
int - वर्तमान ऑब्जेक्ट का हैश कोड।

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectEffectiveData> iterator()
```

एक इटेरेटर लौटाता है जो संग्रह के माध्यम से इटरेट करता है।

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectEffectiveData> - संग्रह के माध्यम से इटरेट करने वाला IGenericEnumerator।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectEffectiveData> iteratorJava()
```

पूरे संग्रह के लिए एक जावा इटेरेटर लौटाता है।

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectEffectiveData> - पूरे संग्रह के लिए java.util.Iterator।

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

सभी तत्वों को संग्रह से निर्दिष्ट एरे में कॉपी करता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | भरने के लिए एरे। |
| index | int | लक्ष्य एरे में प्रारंभिक स्थिति। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

संकलन तक पहुँच सिंक्रनाइज़्ड (थ्रेड-सुरक्षित) है या नहीं, इसका मान लौटाता है। केवल-पढ़ने-योग्य boolean।

**Returns:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

एक सिंक्रनाइज़ेशन रूट लौटाता है। केवल-पढ़ने-योग्य Object।

**Returns:**
java.lang.Object