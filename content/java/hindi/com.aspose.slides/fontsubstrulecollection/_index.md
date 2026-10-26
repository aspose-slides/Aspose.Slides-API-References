---
title: FontSubstRuleCollection
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: फ़ॉन्ट प्रतिस्थापन का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/fontsubstrulecollection/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
```
public class FontSubstRuleCollection implements IFontSubstRuleCollection
```

फ़ॉन्ट प्रतिस्थापन का संग्रह दर्शाता है।

## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [FontSubstRuleCollection()](#FontSubstRuleCollection--) |  |

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [size()](#size--) | संग्रह में वास्तविक तौर पर निहित तत्वों की संख्या प्राप्त करता है। |
| [add(IFontSubstRule value)](#add-com.aspose.slides.IFontSubstRule-) | नए फ़ॉन्ट प्रतिस्थापन नियम को संग्रह में जोड़ता है। |
| [remove(IFontSubstRule value)](#remove-com.aspose.slides.IFontSubstRule-) | किसी विशिष्ट वस्तु की पहली घटना को संग्रह से हटाता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। |
| [iterator()](#iterator--) | एक एनेमरेटर लौटाता है जो संग्रह के माध्यम से इटरेट करता है। |
| [iteratorJava()](#iteratorJava--) | पूरा संग्रह के लिए जावा इटररेटर लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | सभी तत्वों को संग्रह से निर्दिष्ट ऐरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो दर्शाता है कि क्या संग्रह तक पहुंच सिंक्रोनाइज़्ड (थ्रेड-सेफ़) है। |
| [getSyncRoot()](#getSyncRoot--) | एक सिंक्रोनाइज़ेशन रूट लौटाता है। |

### FontSubstRuleCollection() {#FontSubstRuleCollection--}
```
public FontSubstRuleCollection()
```

### size() {#size--}
```
public final int size()
```

संग्रह में वास्तविक तौर पर निहित तत्वों की संख्या प्राप्त करता है। केवल-पढ़ने योग्य int.

**रिटर्न:**
int

### add(IFontSubstRule value) {#add-com.aspose.slides.IFontSubstRule-}
```
public final void add(IFontSubstRule value)
```

नए फ़ॉन्ट प्रतिस्थापन नियम को संग्रह में जोड़ता है

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |  |

### remove(IFontSubstRule value) {#remove-com.aspose.slides.IFontSubstRule-}
```
public final void remove(IFontSubstRule value)
```

किसी विशिष्ट वस्तु की पहली घटना को संग्रह से हटाता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | संग्रह से हटाने के लिए फ़ॉन्ट प्रतिस्थापन नियम। |

### get_Item(int index) {#get-Item-int-}
```
public final IFontSubstRule get_Item(int index)
```

निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontSubstRule> iterator()
```

एक एनेमरेटर लौटाता है जो संग्रह के माध्यम से इटरेट करता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontSubstRule> - एक IGenericEnumerator जो संग्रह के माध्यम से इटरेट करने के लिए उपयोग किया जा सकता है।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontSubstRule> iteratorJava()
```

पूरा संग्रह के लिए जावा इटररेटर लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontSubstRule> - पूरा संग्रह के लिए एक java.util.Iterator।

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

सभी तत्वों को संग्रह से निर्दिष्ट ऐरे में कॉपी करता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य ऐरे। |
| index | int | लक्ष्य ऐरे में प्रारंभिक सूचकांक। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

एक मान लौटाता है जो दर्शाता है कि क्या संग्रह तक पहुंच सिंक्रोनाइज़्ड (थ्रेड-सेफ़) है। केवल-पढ़ने योग्य boolean।

**रिटर्न:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

एक सिंक्रोनाइज़ेशन रूट लौटाता है। केवल-पढ़ने योग्य Object।

**रिटर्न:**
java.lang.Object