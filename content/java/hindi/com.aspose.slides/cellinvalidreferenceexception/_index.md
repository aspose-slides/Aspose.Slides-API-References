---
title: CellInvalidReferenceException
second_title: Aspose.Slides के लिए Java API संदर्भ
description: एक अमान्य सेल रेफ़रेंस मिलने पर उत्पन्न होने वाला अपवाद।
type: docs
url: /hi/com.aspose.slides/cellinvalidreferenceexception/
---
**विरासत:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidReferenceException extends PptxEditException
```

एक अमान्य सेल रेफ़रेंस मिलने पर फेंका गया अपवाद।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [CellInvalidReferenceException()](#CellInvalidReferenceException--) | एक नया उदाहरण प्रारम्भ करता है [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) क्लास का। |
| [CellInvalidReferenceException(String message)](#CellInvalidReferenceException-java.lang.String-) | एक नया उदाहरण प्रारम्भ करता है [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) क्लास का, जिसमें निर्दिष्ट त्रुटि संदेश होता है। |
| [CellInvalidReferenceException(String message, RuntimeException innerException)](#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-) | एक नया उदाहरण प्रारम्भ करता है [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) क्लास का, जिसमें निर्दिष्ट त्रुटि संदेश और इस अपवाद के कारण वाली आन्तरिक अपवाद का संदर्भ होता है। |
| [CellInvalidReferenceException(String message, String reference)](#CellInvalidReferenceException-java.lang.String-java.lang.String-) | एक नया उदाहरण प्रारम्भ करता है [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) क्लास का, जिसमें निर्दिष्ट त्रुटि संदेश और एक अमान्य सेल रेफ़रेंस होता है। |

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getReference()](#getReference--) | एक अमान्य सेल रेफ़रेंस प्राप्त करता है। |

### CellInvalidReferenceException() {#CellInvalidReferenceException--}
```
public CellInvalidReferenceException()
```

एक नया उदाहरण प्रारम्भ करता है [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) क्लास का।

### CellInvalidReferenceException(String message) {#CellInvalidReferenceException-java.lang.String-}
```
public CellInvalidReferenceException(String message)
```

एक नया उदाहरण प्रारम्भ करता है [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) क्लास का, जिसमें निर्दिष्ट त्रुटि संदेश होता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| message | java.lang.String | त्रुटि का वर्णन करने वाली स्ट्रिंग। |

### CellInvalidReferenceException(String message, RuntimeException innerException) {#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidReferenceException(String message, RuntimeException innerException)
```

एक नया उदाहरण प्रारम्भ करता है [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) क्लास का, जिसमें निर्दिष्ट त्रुटि संदेश और इस अपवाद के कारण वाली आन्तरिक अपवाद का संदर्भ होता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| message | java.lang.String | त्रुटि का वर्णन करने वाली स्ट्रिंग। |
| innerException | java.lang.RuntimeException | वर्तमान अपवाद के कारण वाली अपवाद। |

### CellInvalidReferenceException(String message, String reference) {#CellInvalidReferenceException-java.lang.String-java.lang.String-}
```
public CellInvalidReferenceException(String message, String reference)
```

एक नया उदाहरण प्रारम्भ करता है [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) क्लास का, जिसमें निर्दिष्ट त्रुटि संदेश और एक अमान्य सेल रेफ़रेंस होता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| message | java.lang.String | त्रुटि का वर्णन करने वाली स्ट्रिंग। |
| reference | java.lang.String | एक अमान्य सेल रेफ़रेंस। |

### getReference() {#getReference--}
```
public final String getReference()
```

एक अमान्य सेल रेफ़रेंस प्राप्त करता है।

**Returns:**
java.lang.String