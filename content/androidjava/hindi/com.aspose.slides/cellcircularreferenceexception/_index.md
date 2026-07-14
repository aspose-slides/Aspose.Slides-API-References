---
title: CellCircularReferenceException
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक या अधिक गोलाकार रेफ़रेंस का पता चलने पर, जब कोई फ़ॉर्मूला सीधे या परोक्ष रूप से अपने स्वयं के सेल को संदर्भित करता है, तब फेंकी जाने वाली अपवाद।
type: docs
url: /hi/com.aspose.slides/cellcircularreferenceexception/
---
**विरासत:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellCircularReferenceException extends PptxEditException
```

एक या अधिक गोलाकार रेफ़रेंस का पता चलने पर, जब कोई फ़ॉर्मूला सीधे या परोक्ष रूप से अपने स्वयं के सेल को संदर्भित करता है, तब फेंकी जाने वाली अपवाद।

## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [CellCircularReferenceException()](#CellCircularReferenceException--) | [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) क्लास का एक नया उदाहरण प्रारंभ करता है। |
| [CellCircularReferenceException(String message)](#CellCircularReferenceException-java.lang.String-) | [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) क्लास का एक नया उदाहरण एक निर्दिष्ट त्रुटि संदेश के साथ प्रारंभ करता है। |
| [CellCircularReferenceException(String message, RuntimeException innerException)](#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-) | [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) क्लास का एक नया उदाहरण एक निर्दिष्ट त्रुटि संदेश और इस अपवाद के कारण वाले आंतरिक अपवाद का संदर्भ के साथ प्रारंभ करता है। |
| [CellCircularReferenceException(String message, String reference)](#CellCircularReferenceException-java.lang.String-java.lang.String-) | [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) क्लास का एक नया उदाहरण एक निर्दिष्ट त्रुटि संदेश और गोलाकार सेल रेफ़रेंस के साथ प्रारंभ करता है। |

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getReference()](#getReference--) | एक गोलाकार सेल रेफ़रेंस प्राप्त करता है। |

### CellCircularReferenceException() {#CellCircularReferenceException--}
```
public CellCircularReferenceException()
```

[CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) क्लास का एक नया उदाहरण प्रारंभ करता है।

### CellCircularReferenceException(String message) {#CellCircularReferenceException-java.lang.String-}
```
public CellCircularReferenceException(String message)
```

[CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) क्लास का एक नया उदाहरण एक निर्दिष्ट त्रुटि संदेश के साथ प्रारंभ करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| message | java.lang.String | त्रुटि को वर्णन करने वाली एक स्ट्रिंग। |

### CellCircularReferenceException(String message, RuntimeException innerException) {#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellCircularReferenceException(String message, RuntimeException innerException)
```

[CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) क्लास का एक नया उदाहरण एक निर्दिष्ट त्रुटि संदेश और इस अपवाद के कारण वाले आंतरिक अपवाद का संदर्भ के साथ प्रारंभ करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| message | java.lang.String | त्रुटि को वर्णन करने वाली एक स्ट्रिंग। |
| innerException | java.lang.RuntimeException | वर्तमान अपवाद का कारण बनने वाला अपवाद। |

### CellCircularReferenceException(String message, String reference) {#CellCircularReferenceException-java.lang.String-java.lang.String-}
```
public CellCircularReferenceException(String message, String reference)
```

[CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) क्लास का एक नया उदाहरण एक निर्दिष्ट त्रुटि संदेश और गोलाकार सेल रेफ़रेंस के साथ प्रारंभ करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| message | java.lang.String | त्रुटि को वर्णन करने वाली एक स्ट्रिंग। |
| reference | java.lang.String | एक गोलाकार सेल रेफ़रेंस। |

### getReference() {#getReference--}
```
public final String getReference()
```

एक गोलाकार सेल रेफ़रेंस प्राप्त करता है।

**रिटर्न मान:**
java.lang.String