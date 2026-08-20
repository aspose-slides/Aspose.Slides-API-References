---
title: ILineFillFormatEffectiveData
second_title: Aspose.Slides के लिए Java API संदर्भ
description: अप्रिवर्तनीय ऑब्जेक्ट जिसमें प्रभावी लाइन भरने की विशेषताएँ शामिल हैं।
type: docs
url: /hi/com.aspose.slides/ilinefillformateffectivedata/
---
**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormatEffectiveData extends IFillParamSource
```

अपरिवर्तनीय ऑब्जेक्ट जिसमें प्रभावी लाइन भरने की विशेषताएँ होती हैं।

--------------------

This interface is used as a part of [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getFillType()](#getFillType--) | फिल प्रकार को लौटाता है। |
| [getSolidFillColor()](#getSolidFillColor--) | सॉलिड फ़िल का रंग लौटाता है। |
| [getGradientFormat()](#getGradientFormat--) | ग्रेडिएंट फ़िल प्रारूप को लौटाता है। |
| [getPatternFormat()](#getPatternFormat--) | पैटर्न फ़िल प्रारूप को लौटाता है। |
| [getRotateWithShape()](#getRotateWithShape--) | निर्धारित करता है कि फ़िल को आकार के साथ घुमाया जाना चाहिए या नहीं। |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

फिल प्रकार को लौटाता है। केवल-पढ़ने योग्य [FillType](../../com.aspose.slides/filltype).

**रिटर्न:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Color getSolidFillColor()
```

सॉलिड फ़िल का रंग लौटाता है। केवल-पढ़ने योग्य java.awt.Color.

**रिटर्न:**
java.awt.Color
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```

ग्रेडिएंट फ़िल प्रारूप को लौटाता है। केवल-पढ़ने योग्य [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**रिटर्न:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```

पैटर्न फ़िल प्रारूप को लौटाता है। केवल-पढ़ने योग्य [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**रिटर्न:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```

निर्धारित करता है कि फ़िल को आकार के साथ घुमाया जाना चाहिए या नहीं। केवल-पढ़ने योग्य boolean.

**रिटर्न:**
boolean