---
title: CellInvalidReferenceException
second_title: Aspose.Slides for Android के माध्यम से Java API संदर्भ
description: जब कोई अमान्य सेल रेफ़रेंस मिलता है तो फेंका जाने वाला अपवाद।
type: docs
url: /hi/com.aspose.slides/cellinvalidreferenceexception/
---
**विरासत:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidReferenceException extends PptxEditException
```

जब कोई अमान्य सेल रेफ़रेंस मिलता है तो यह अपवाद फेंका जाता है।
## कंस्ट्रक्टर

| निर्माता | विवरण |
| --- | --- |
| [CellInvalidReferenceException()](#CellInvalidReferenceException--) | एक नया [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) क्लास का उदाहरण इनिशियलाइज़ करता है। |
| [CellInvalidReferenceException(String message)](#CellInvalidReferenceException-java.lang.String-) | एक निर्दिष्ट त्रुटि संदेश के साथ एक नया [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) क्लास का उदाहरण इनिशियलाइज़ करता है। |
| [CellInvalidReferenceException(String message, RuntimeException innerException)](#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-) | एक निर्दिष्ट त्रुटि संदेश और एक आंतरिक अपवाद का संदर्भ जिसके कारण यह अपवाद हुआ, के साथ एक नया [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) क्लास का उदाहरण इनिशियलाइज़ करता है। |
| [CellInvalidReferenceException(String message, String reference)](#CellInvalidReferenceException-java.lang.String-java.lang.String-) | एक निर्दिष्ट त्रुटि संदेश और एक अमान्य सेल रेफ़रेंस के साथ एक नया [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) क्लास का उदाहरण इनिशियलाइज़ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getReference()](#getReference--) | एक अमान्य सेल रेफ़रेंस प्राप्त करता है। |
### CellInvalidReferenceException() {#CellInvalidReferenceException--}
```
public CellInvalidReferenceException()
```

एक नया [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) क्लास का उदाहरण इनिशियलाइज़ करता है।

### CellInvalidReferenceException(String message) {#CellInvalidReferenceException-java.lang.String-}
```
public CellInvalidReferenceException(String message)
```

एक नया [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) क्लास का उदाहरण एक निर्दिष्ट त्रुटि संदेश के साथ इनिशियलाइज़ करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| message | java.lang.String | एक स्ट्रिंग जो त्रुटि का वर्णन करती है। |

### CellInvalidReferenceException(String message, RuntimeException innerException) {#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidReferenceException(String message, RuntimeException innerException)
```

एक नया [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) क्लास का उदाहरण एक निर्दिष्ट त्रुटि संदेश और एक आंतरिक अपवाद का संदर्भ जिसके कारण यह अपवाद हुआ, के साथ इनिशियलाइज़ करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| message | java.lang.String | एक स्ट्रिंग जो त्रुटि का वर्णन करती है। |
| innerException | java.lang.RuntimeException | वर्तमान अपवाद का कारण बनने वाला अपवाद। |

### CellInvalidReferenceException(String message, String reference) {#CellInvalidReferenceException-java.lang.String-java.lang.String-}
```
public CellInvalidReferenceException(String message, String reference)
```

एक नया [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) क्लास का उदाहरण एक निर्दिष्ट त्रुटि संदेश और एक अमान्य सेल रेफ़रेंस के साथ इनिशियलाइज़ करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| message | java.lang.String | एक स्ट्रिंग जो त्रुटि का वर्णन करती है। |
| reference | java.lang.String | एक अमान्य सेल रेफ़रेंस। |

### getReference() {#getReference--}
```
public final String getReference()
```

एक अमान्य सेल रेफ़रेंस प्राप्त करता है।

**वापसी मान:**
java.lang.String