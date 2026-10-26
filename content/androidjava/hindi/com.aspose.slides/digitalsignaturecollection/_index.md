---
title: DigitalSignatureCollection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक दस्तावेज़ से जुड़ी डिजिटल हस्ताक्षरों के संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/digitalsignaturecollection/
---
**विरासत:**  
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)  
```
public class DigitalSignatureCollection extends DomObject<Presentation> implements IDigitalSignatureCollection
```

दस्तावेज़ से जुड़ी डिजिटल हस्ताक्षरों का संग्रह दर्शाता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट सूचकांक पर हस्ताक्षर लौटाता है। |
| [add(IDigitalSignature signature)](#add-com.aspose.slides.IDigitalSignature-) | संग्रह के अंत में हस्ताक्षर जोड़ता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट सूचकांक पर हस्ताक्षर हटाता है। |
| [clear()](#clear--) | संग्रह से सभी हस्ताक्षर हटाता है। |
| [iterator()](#iterator--) | एक इटेरेटर लौटाता है जो संग्रह को इटेरेट करता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए एक जावा इटेरेटर लौटाता है। |
| [size()](#size--) | संग्रह में तत्वों की संख्या लौटाता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो दर्शाता है कि क्या संग्रह तक पहुंच समकालिक (थ्रेड-सेफ़) है। |
| [getSyncRoot()](#getSyncRoot--) | समकालन मूल लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | सभी तत्वों को संग्रह से निर्दिष्ट ऐरे में कॉपी करता है। |

### get_Item(int index) {#get-Item-int-}
```
public final IDigitalSignature get_Item(int index)
```

निर्दिष्ट सूचकांक पर हस्ताक्षर लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**वापसी:**
[IDigitalSignature](../../com.aspose.slides/idigitalsignature)

### add(IDigitalSignature signature) {#add-com.aspose.slides.IDigitalSignature-}
```
public final void add(IDigitalSignature signature)
```

संग्रह के अंत में हस्ताक्षर जोड़ता है।

--------------------

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

निर्दिष्ट सूचकांक पर हस्ताक्षर हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | वह सूचकांक जिससे हस्ताक्षर हटाना है। |

### clear() {#clear--}
```
public final void clear()
```

संग्रह से सभी हस्ताक्षर हटाता है।

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDigitalSignature> iterator()
```

एक इटेरेटर लौटाता है जो संग्रह को इटेरेट करता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDigitalSignature> - एक IGenericEnumerator जिसका उपयोग संग्रह को इटेरेट करने के लिए किया जा सकता है।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDigitalSignature> iteratorJava()
```

पूरे संग्रह के लिए एक जावा इटेरेटर लौटाता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDigitalSignature> - एक java.util.Iterator जो पूरे संग्रह के लिए उपयोग किया जाता है।

### size() {#size--}
```
public final int size()
```

संग्रह में तत्वों की संख्या लौटाता है। केवल पढ़ने योग्य int।

**वापसी:**
int

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

एक मान लौटाता है जो दर्शाता है कि क्या संग्रह तक पहुंच समकालिक (थ्रेड-सेफ़) है। केवल पढ़ने योग्य boolean।

**वापसी:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

समकालन मूल लौटाता है। केवल पढ़ने योग्य Object।

**वापसी:**
java.lang.Object

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

सभी तत्वों को संग्रह से निर्दिष्ट ऐरे में कॉपी करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य ऐरे। |
| index | int | लक्ष्य ऐरे में प्रारंभिक सूचकांक। |