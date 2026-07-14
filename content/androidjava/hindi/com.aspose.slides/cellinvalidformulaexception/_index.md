---
title: CellInvalidFormulaException
second_title: Aspose.Slides for Android द्वारा Java API संदर्भ
description: जब गणना किया गया फ़ॉर्मूला सही नहीं होता या पार्स नहीं किया जाता है, तो फेंका जाने वाला अपवाद।
type: docs
url: /hi/com.aspose.slides/cellinvalidformulaexception/
---
**विरासत:**  
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidFormulaException extends PptxEditException
```

गणना किया गया फ़ॉर्मूला सही न होने या पार्स न किए जाने पर फेंका गया अपवाद।

## कंस्ट्रक्टर्स

| Constructor | Description |
| --- | --- |
| [CellInvalidFormulaException()](#CellInvalidFormulaException--) | [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) क्लास का नया उदाहरण आरंभ करता है। |
| [CellInvalidFormulaException(String message)](#CellInvalidFormulaException-java.lang.String-) | निर्दिष्ट त्रुटि संदेश के साथ [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) क्लास का नया उदाहरण आरंभ करता है। |
| [CellInvalidFormulaException(String message, RuntimeException innerException)](#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-) | निर्दिष्ट त्रुटि संदेश और उस आंतरिक अपवाद का संदर्भ जिसके कारण यह अपवाद हुआ, के साथ [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) क्लास का नया उदाहरण आरंभ करता है। |
| [CellInvalidFormulaException(String message, String reference)](#CellInvalidFormulaException-java.lang.String-java.lang.String-) | निर्दिष्ट त्रुटि संदेश और वह सेल रेफ़रेंस जिसके भीतर अमान्य फ़ॉर्मूला है, के साथ [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) क्लास का नया उदाहरण आरंभ करता है। |

## मेथड्स

| Method | Description |
| --- | --- |
| [getReference()](#getReference--) | वह सेल रेफ़रेंस प्राप्त करता है जिसमें अमान्य फ़ॉर्मूला है। |

### CellInvalidFormulaException() {#CellInvalidFormulaException--}
```
public CellInvalidFormulaException()
```

[CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) क्लास का नया उदाहरण आरंभ करता है।

### CellInvalidFormulaException(String message) {#CellInvalidFormulaException-java.lang.String-}
```
public CellInvalidFormulaException(String message)
```

निर्दिष्ट त्रुटि संदेश के साथ [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) क्लास का नया उदाहरण आरंभ करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| message | java.lang.String | त्रुटि का वर्णन करने वाला स्ट्रिंग। |

### CellInvalidFormulaException(String message, RuntimeException innerException) {#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidFormulaException(String message, RuntimeException innerException)
```

निर्दिष्ट त्रुटि संदेश और उस आंतरिक अपवाद का संदर्भ जिसके कारण यह अपवाद हुआ, के साथ [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) क्लास का नया उदाहरण आरंभ करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| message | java.lang.String | त्रुटि का वर्णन करने वाला स्ट्रिंग। |
| innerException | java.lang.RuntimeException | वर्तमान अपवाद का कारण बनने वाला अपवाद। |

### CellInvalidFormulaException(String message, String reference) {#CellInvalidFormulaException-java.lang.String-java.lang.String-}
```
public CellInvalidFormulaException(String message, String reference)
```

निर्दिष्ट त्रुटि संदेश और वह सेल रेफ़रेंस जिसके भीतर अमान्य फ़ॉर्मूला है, के साथ [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) क्लास का नया उदाहरण आरंभ करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| message | java.lang.String | त्रुटि का वर्णन करने वाला स्ट्रिंग। |
| reference | java.lang.String | आंतरिक अपवाद के रेफ़रेंस का वर्णन करने वाला स्ट्रिंग। |

### getReference() {#getReference--}
```
public final String getReference()
```

अमान्य फ़ॉर्मूला वाले सेल रेफ़रेंस को प्राप्त करता है।

**रिटर्न:**
java.lang.String