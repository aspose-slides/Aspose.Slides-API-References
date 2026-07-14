---
title: FontSubstRuleCollection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: फ़ॉन्ट प्रतिस्थापन के संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/fontsubstrulecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
```
public class FontSubstRuleCollection implements IFontSubstRuleCollection
```

फ़ॉन्ट बदलने के संग्रह का प्रतिनिधित्व करता है।
## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [FontSubstRuleCollection()](#FontSubstRuleCollection--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [size()](#size--) | संग्रह में वास्तव में उपस्थित तत्वों की संख्या प्राप्त करता है। |
| [add(IFontSubstRule value)](#add-com.aspose.slides.IFontSubstRule-) | नई फ़ॉन्ट बदलने की नियम को संग्रह में जोड़ता है |
| [remove(IFontSubstRule value)](#remove-com.aspose.slides.IFontSubstRule-) | संग्रह से किसी विशिष्ट वस्तु की पहली उपस्थिति को हटाता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है। |
| [iterator()](#iterator--) | एक एनेमरेटर लौटाता है जो संग्रह के माध्यम से इटररेट करता है। |
| [iteratorJava()](#iteratorJava--) | पूरी संग्रह के लिए एक java इटरटर लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | सभी तत्वों को संग्रह से निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | यह लौटाता है कि क्या संग्रह तक पहुँच समन्वित (थ्रेड-सेफ़) है। |
| [getSyncRoot()](#getSyncRoot--) | एक समन्वयन रूट लौटाता है। |
### FontSubstRuleCollection() {#FontSubstRuleCollection--}
```
public FontSubstRuleCollection()
```


### size() {#size--}
```
public final int size()
```


संग्रह में वास्तव में उपस्थित तत्वों की संख्या प्राप्त करता है। केवल पढ़ने योग्य int.

**रिटर्न:**
int
### add(IFontSubstRule value) {#add-com.aspose.slides.IFontSubstRule-}
```
public final void add(IFontSubstRule value)
```


नई फ़ॉन्ट बदलने की नियम को संग्रह में जोड़ता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |  |

### remove(IFontSubstRule value) {#remove-com.aspose.slides.IFontSubstRule-}
```
public final void remove(IFontSubstRule value)
```


संग्रह से किसी विशिष्ट वस्तु की पहली उपस्थिति को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | संग्रह से हटाने के लिए फ़ॉन्ट बदलने का नियम। |

### get_Item(int index) {#get-Item-int-}
```
public final IFontSubstRule get_Item(int index)
```


निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[IFontSubstRule](../../com.aspose.slides/ifontsubstrule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontSubstRule> iterator()
```


संग्रह के माध्यम से इटररेट करने वाला एक एनेमरेटर लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontSubstRule> - एक IGenericEnumerator जिसका उपयोग संग्रह के माध्यम से इटररेट करने के लिए किया जा सकता है।
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontSubstRule> iteratorJava()
```


पूरी संग्रह के लिए एक java इटरटर लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontSubstRule> - पूरी संग्रह के लिए एक java.util.Iterator।
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


सभी तत्वों को संग्रह से निर्दिष्ट एरे में कॉपी करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य एरे। |
| index | int | लक्ष्य एरे में शुरुआती इंडेक्स। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


यह लौटाता है कि क्या संग्रह तक पहुँच समन्वित (थ्रेड-सेफ़) है। केवल पढ़ने योग्य boolean.

**रिटर्न:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


एक समन्वयन रूट लौटाता है। केवल पढ़ने योग्य Object.

**रिटर्न:**
java.lang.Object