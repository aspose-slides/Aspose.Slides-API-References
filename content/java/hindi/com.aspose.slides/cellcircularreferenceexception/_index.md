---
title: CellCircularReferenceException
second_title: Aspose.Slides के लिए Java API संदर्भ
description: एक अपवाद जो तब फेंका जाता है जब एक या अधिक चक्रीय संदर्भ पाए जाते हैं जहाँ कोई सूत्र सीधे या परोक्ष रूप से अपने स्वयं के सेल को संदर्भित करता है।
type: docs
url: /hi/com.aspose.slides/cellcircularreferenceexception/
---
**विरासत:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellCircularReferenceException extends PptxEditException
```

जब एक या अधिक चक्रीय संदर्भ पाए जाते हैं जहाँ कोई सूत्र सीधे या परोक्ष रूप से अपने स्वयं के सेल को संदर्भित करता है, तब यह अपवाद फेंका जाता है।

## कन्स्ट्रक्टर्स

| निर्माता | विवरण |
| --- | --- |
| [CellCircularReferenceException()](#CellCircularReferenceException--) | [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) क्लास का नया उदाहरण प्रारंभ करता है। |
| [CellCircularReferenceException(String message)](#CellCircularReferenceException-java.lang.String-) | [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) क्लास का नया उदाहरण एक निर्दिष्ट त्रुटि संदेश के साथ प्रारंभ करता है। |
| [CellCircularReferenceException(String message, RuntimeException innerException)](#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-) | [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) क्लास का नया उदाहरण एक निर्दिष्ट त्रुटि संदेश और इस अपवाद का कारण बनने वाले आंतरिक अपवाद के संदर्भ के साथ प्रारंभ करता है। |
| [CellCircularReferenceException(String message, String reference)](#CellCircularReferenceException-java.lang.String-java.lang.String-) | [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) क्लास का नया उदाहरण एक निर्दिष्ट त्रुटि संदेश और चक्रीय सेल संदर्भ के साथ प्रारंभ करता है। |

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getReference()](#getReference--) | एक चक्रीय सेल संदर्भ प्राप्त करता है। |

### CellCircularReferenceException() {#CellCircularReferenceException--}
```
public CellCircularReferenceException()
```

[CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) क्लास का नया उदाहरण प्रारंभ करता है।

### CellCircularReferenceException(String message) {#CellCircularReferenceException-java.lang.String-}
```
public CellCircularReferenceException(String message)
```

[CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) क्लास का नया उदाहरण एक निर्दिष्ट त्रुटि संदेश के साथ प्रारंभ करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| message | java.lang.String | एक स्ट्रिंग जो त्रुटि का वर्णन करती है। |

### CellCircularReferenceException(String message, RuntimeException innerException) {#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellCircularReferenceException(String message, RuntimeException innerException)
```

[CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) क्लास का नया उदाहरण एक निर्दिष्ट त्रुटि संदेश और इस अपवाद का कारण बनने वाले आंतरिक अपवाद के संदर्भ के साथ प्रारंभ करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| message | java.lang.String | एक स्ट्रिंग जो त्रुटि का वर्णन करती है। |
| innerException | java.lang.RuntimeException | वर्तमान अपवाद का कारण बनने वाला अपवाद। |

### CellCircularReferenceException(String message, String reference) {#CellCircularReferenceException-java.lang.String-java.lang.String-}
```
public CellCircularReferenceException(String message, String reference)
```

[CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) क्लास का नया उदाहरण एक निर्दिष्ट त्रुटि संदेश और चक्रीय सेल संदर्भ के साथ प्रारंभ करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| message | java.lang.String | एक स्ट्रिंग जो त्रुटि का वर्णन करती है। |
| reference | java.lang.String | एक चक्रीय सेल संदर्भ। |

### getReference() {#getReference--}
```
public final String getReference()
```

एक चक्रीय सेल संदर्भ प्राप्त करता है।

**रिटर्न:**
java.lang.String