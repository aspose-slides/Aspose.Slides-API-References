---
title: CellInvalidFormulaException
second_title: Aspose.Slides for Java API संदर्भ
description: एक अपवाद जो तब उत्पन्न होता है जब गणना किया गया सूत्र सही नहीं होता या पार्स नहीं हो पाता है।
type: docs
url: /hi/com.aspose.slides/cellinvalidformulaexception/
---
**विरासत:**  
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidFormulaException extends PptxEditException
```

एक अपवाद जो तब उत्पन्न होता है जब गणना किया गया सूत्र सही नहीं होता या पार्स नहीं हो पाता है।

## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [CellInvalidFormulaException()](#CellInvalidFormulaException--) | [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) वर्ग का नया उदाहरण प्रारंभ करता है। |
| [CellInvalidFormulaException(String message)](#CellInvalidFormulaException-java.lang.String-) | [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) वर्ग का नया उदाहरण निर्दिष्ट त्रुटि संदेश के साथ प्रारंभ करता है। |
| [CellInvalidFormulaException(String message, RuntimeException innerException)](#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-) | [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) वर्ग का नया उदाहरण निर्दिष्ट त्रुटि संदेश और अंदरूनी अपवाद के संदर्भ के साथ प्रारंभ करता है जो इस अपवाद का कारण है। |
| [CellInvalidFormulaException(String message, String reference)](#CellInvalidFormulaException-java.lang.String-java.lang.String-) | [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) वर्ग का नया उदाहरण निर्दिष्ट त्रुटि संदेश और अमान्य सूत्र वाला सेल संदर्भ के साथ प्रारंभ करता है। |

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getReference()](#getReference--) | अमान्य सूत्र वाला सेल संदर्भ प्राप्त करता है। |
### CellInvalidFormulaException() {#CellInvalidFormulaException--}
```
public CellInvalidFormulaException()
```

[CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) वर्ग का नया उदाहरण प्रारंभ करता है।

### CellInvalidFormulaException(String message) {#CellInvalidFormulaException-java.lang.String-}
```
public CellInvalidFormulaException(String message)
```

[CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) वर्ग का नया उदाहरण निर्दिष्ट त्रुटि संदेश के साथ प्रारंभ करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| message | java.lang.String | त्रुटि का वर्णन करने वाली स्ट्रिंग। |

### CellInvalidFormulaException(String message, RuntimeException innerException) {#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidFormulaException(String message, RuntimeException innerException)
```

[CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) वर्ग का नया उदाहरण निर्दिष्ट त्रुटि संदेश और अंदरूनी अपवाद के संदर्भ के साथ प्रारंभ करता है जो इस अपवाद का कारण है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| message | java.lang.String | त्रुटि का वर्णन करने वाली स्ट्रिंग। |
| innerException | java.lang.RuntimeException | वर्तमान अपवाद का कारण बनने वाला अपवाद। |

### CellInvalidFormulaException(String message, String reference) {#CellInvalidFormulaException-java.lang.String-java.lang.String-}
```
public CellInvalidFormulaException(String message, String reference)
```

[CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) वर्ग का नया उदाहरण निर्दिष्ट त्रुटि संदेश और अमान्य सूत्र वाला सेल संदर्भ के साथ प्रारंभ करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| message | java.lang.String | त्रुटि का वर्णन करने वाली स्ट्रिंग। |
| reference | java.lang.String | अंदरूनी अपवाद के संदर्भ का विवरण देने वाली स्ट्रिंग। |

### getReference() {#getReference--}
```
public final String getReference()
```

अमान्य सूत्र वाला सेल संदर्भ प्राप्त करता है।

**रिटर्न:**  
java.lang.String