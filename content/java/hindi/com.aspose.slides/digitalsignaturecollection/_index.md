---
title: DigitalSignatureCollection
second_title: Aspose.Slides for Java API संदर्भ
description: डॉक्यूमेंट से जुड़ी डिजिटल हस्ताक्षरों का एक संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/digitalsignaturecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)
```
public class DigitalSignatureCollection extends DomObject<Presentation> implements IDigitalSignatureCollection
```

डिजिटल हस्ताक्षरों का एक संग्रह दर्शाता है जो दस्तावेज़ से जुड़ा है।
## मेथड्स

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | इंडेक्स द्वारा हस्ताक्षर लौटाता है। |
| [add(IDigitalSignature signature)](#add-com.aspose.slides.IDigitalSignature-) | संग्रह के अंत में हस्ताक्षर जोड़ता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट इंडेक्स पर हस्ताक्षर हटाता है। |
| [clear()](#clear--) | संग्रह से सभी हस्ताक्षर हटाता है। |
| [iterator()](#iterator--) | एक एनोमरेटर लौटाता है जो संग्रह के माध्यम से इटरैट करता है। |
| [iteratorJava()](#iteratorJava--) | पूरा संग्रह के लिए एक जावा इटेरेटर लौटाता है। |
| [size()](#size--) | संग्रह में तत्वों की संख्या लौटाता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो इंगित करता है कि संग्रह तक पहुंच समकालिक (थ्रेड-सेफ़) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | एक समकालिकता मूल (synchronization root) लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | संग्रह के सभी तत्व निर्दिष्ट सरणी में कॉपी करता है। |
### get_Item(int index) {#get-Item-int-}
```
public final IDigitalSignature get_Item(int index)
```

इंडेक्स द्वारा हस्ताक्षर लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[IDigitalSignature](../../com.aspose.slides/idigitalsignature)
### add(IDigitalSignature signature) {#add-com.aspose.slides.IDigitalSignature-}
```
public final void add(IDigitalSignature signature)
```

संग्रह के अंत में हस्ताक्षर जोड़ता है।

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      signature.setComments("Aspose.Slides digital signing test.");
>      pres.getDigitalSignatures().add(signature);
>      pres.save("SomePresentationSigned.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| signature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | जोड़ने के लिए हस्ताक्षर। |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

निर्दिष्ट इंडेक्स पर हस्ताक्षर हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हस्ताक्षर का वह इंडेक्स जिसे हटाना है। |
### clear() {#clear--}
```
public final void clear()
```

संग्रह से सभी हस्ताक्षर हटाता है।

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDigitalSignature> iterator()
```

एक एनोमरेटर लौटाता है जो संग्रह के माध्यम से इटरैट करता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDigitalSignature> - एक IGenericEnumerator जो संग्रह के माध्यम से इटरैट करने के लिए उपयोग किया जा सकता है।
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDigitalSignature> iteratorJava()
```

एक एनोमरेटर लौटाता है जो संग्रह के माध्यम से इटरैट करता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDigitalSignature> - पूरा संग्रह के लिए एक java.util.Iterator।
### size() {#size--}
```
public final int size()
```

संग्रह में तत्वों की संख्या लौटाता है। केवल-पढ़ने योग्य int।

**रिटर्न:**
int
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुंच समकालिक (थ्रेड-सेफ़) है या नहीं। केवल-पढ़ने योग्य boolean।

**रिटर्न:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

एक समकालिकता मूल लौटाता है। केवल-पढ़ने योग्य Object।

**रिटर्न:**
java.lang.Object
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

संग्रह के सभी तत्व निर्दिष्ट सरणी में कॉपी करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्षित सरणी। |
| index | int | लक्षित सरणी में प्रारंभिक इंडेक्स। |