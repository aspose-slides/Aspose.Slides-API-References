---
title: ILineFillFormatEffectiveData
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक अपरिवर्तनीय ऑब्जेक्ट जो प्रभावी लाइन भरने वाले गुणों को समाहित करता है।
type: docs
url: /hi/com.aspose.slides/ilinefillformateffectivedata/
---
**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormatEffectiveData extends IFillParamSource
```

एक अपरिवर्तनीय ऑब्जेक्ट जो प्रभावी लाइन फ़िलिंग गुणों को समाहित करता है।

--------------------

यह इंटरफ़ेस [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) का भाग के रूप में उपयोग किया जाता है।
## विधियां

| विधि | विवरण |
| --- | --- |
| [getFillType()](#getFillType--) | fill type को लौटाता है। |
| [getSolidFillColor()](#getSolidFillColor--) | solid fill का रंग लौटाता है। |
| [getGradientFormat()](#getGradientFormat--) | gradient fill स्वरूप लौटाता है। |
| [getPatternFormat()](#getPatternFormat--) | pattern fill स्वरूप लौटाता है। |
| [getRotateWithShape()](#getRotateWithShape--) | निर्धारित करता है कि क्या fill को shape के साथ घुमाया जाना चाहिए। |

### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

fill type को लौटाता है। केवल-पढ़ने योग्य [FillType](../../com.aspose.slides/filltype)।

**रिटर्न:**
byte

### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Integer getSolidFillColor()
```

solid fill का रंग लौटाता है। केवल-पढ़ने योग्य java.lang.Integer।

**रिटर्न:**
java.lang.Integer

### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```

gradient fill स्वरूप लौटाता है। केवल-पढ़ने योग्य [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)।

**रिटर्न:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)

### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```

pattern fill स्वरूप लौटाता है। केवल-पढ़ने योग्य [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)।

**रिटर्न:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)

### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```

निर्धारित करता है कि क्या fill को shape के साथ घुमाया जाना चाहिए। केवल-पढ़ने योग्य boolean।

**रिटर्न:**
boolean