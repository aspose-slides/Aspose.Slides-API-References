---
title: IFillFormatEffectiveData
second_title: Aspose.Slides जावा के लिए API संदर्भ
description: एक अपरिवर्तनीय वस्तु जिसमें प्रभावी भराव स्वरूपण गुण शामिल हैं।
type: docs
url: /hi/com.aspose.slides/ifillformateffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormatEffectiveData extends IFillParamSource
```

एक अपरिवर्तनीय वस्तु जिसमें प्रभावी भराव स्वरूपण गुण शामिल हैं।

--------------------

यह इंटरफ़ेस [IFillFormat](../../com.aspose.slides/ifillformat) इंटरफ़ेस के साथ उपयोग किया जाता है ताकि विरासत लागू किए हुए प्रभावी स्वरूपण मान लौटाए जा सकें।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getFillType()](#getFillType--) | भराव का प्रकार लौटाता है। |
| [getSolidFillColor()](#getSolidFillColor--) | भराव का रंग लौटाता है। |
| [getSolidFillSchemeColor()](#getSolidFillSchemeColor--) | रंग योजना द्वारा परिभाषित भराव रंग प्राप्त करता है। |
| [getGradientFormat()](#getGradientFormat--) | ग्रेडिएंट भराव स्वरूप लौटाता है। |
| [getPatternFormat()](#getPatternFormat--) | पैटर्न भराव स्वरूप लौटाता है। |
| [getPictureFillFormat()](#getPictureFillFormat--) | चित्र भराव स्वरूप लौटाता है। |
| [getRotateWithShape()](#getRotateWithShape--) | निर्धारित करता है कि क्या भराव को आकार के साथ घुमाया जाना चाहिए। |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


भराव का प्रकार लौटाता है। केवल-पढ़ने योग्य [FillType](../../com.aspose.slides/filltype).

**रिटर्न:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Color getSolidFillColor()
```


भराव का रंग लौटाता है। केवल-पढ़ने योग्य java.awt.Color.

**रिटर्न:**
java.awt.Color
### getSolidFillSchemeColor() {#getSolidFillSchemeColor--}
```
public abstract int getSolidFillSchemeColor()
```


रंग योजना द्वारा परिभाषित भराव रंग प्राप्त करता है। [SchemeColor.NotDefined](../../com.aspose.slides/schemecolor\#NotDefined) मान दर्शाता है कि SolidFillColor (\#getSolidFillColor.getSolidFillColor) एक योजना रंग नहीं है। केवल-पढ़ने योग्य [SchemeColor](../../com.aspose.slides/schemecolor).

**रिटर्न:**
int
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```


ग्रेडिएंट भराव स्वरूप लौटाता है। केवल-पढ़ने योग्य [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**रिटर्न:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```


पैटर्न भराव स्वरूप लौटाता है। केवल-पढ़ने योग्य [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**रिटर्न:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormatEffectiveData getPictureFillFormat()
```


चित्र भराव स्वरूप लौटाता है। केवल-पढ़ने योग्य [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata).

**रिटर्न:**
[IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


निर्धारित करता है कि क्या भराव को आकार के साथ घुमाया जाना चाहिए। केवल-पढ़ने योग्य boolean.

**रिटर्न:**
boolean