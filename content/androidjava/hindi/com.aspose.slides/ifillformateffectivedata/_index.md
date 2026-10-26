---
title: IFillFormatEffectiveData
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक अपरिवर्तनीय वस्तु जो प्रभावी फ़िल फ़ॉर्मेटिंग गुणधर्मों को सम्मिलित करती है।
type: docs
url: /hi/com.aspose.slides/ifillformateffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormatEffectiveData extends IFillParamSource
```

एक अपरिवर्तनीय वस्तु जो प्रभावी फ़िल फ़ॉर्मेटिंग गुणधर्मों को सम्मिलित करती है।

--------------------

यह इंटरफ़ेस [IFillFormat](../../com.aspose.slides/ifillformat) इंटरफ़ेस के साथ मिलकर उपयोग किया जाता है ताकि विरासत लागू होते हुए प्रभावी फ़ॉर्मेटिंग मान लौटाए जा सकें।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getFillType()](#getFillType--) | फ़िलिंग प्रकार लौटाता है। |
| [getSolidFillColor()](#getSolidFillColor--) | फ़िल रंग लौटाता है। |
| [getSolidFillSchemeColor()](#getSolidFillSchemeColor--) | रंग योजना द्वारा निर्धारित फ़िल रंग प्राप्त करता है। |
| [getGradientFormat()](#getGradientFormat--) | ग्रेडिएंट फ़िल फ़ॉर्मेट लौटाता है। |
| [getPatternFormat()](#getPatternFormat--) | पैटर्न फ़िल फ़ॉर्मेट लौटाता है। |
| [getPictureFillFormat()](#getPictureFillFormat--) | चित्र फ़िल फ़ॉर्मेट लौटाता है। |
| [getRotateWithShape()](#getRotateWithShape--) | निर्धारित करता है कि फ़िल को आकार के साथ घुमाया जाना चाहिए या नहीं। |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

फ़िलिंग प्रकार लौटाता है। केवल-पढ़ने योग्य [FillType](../../com.aspose.slides/filltype)।

**रिटर्न:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Integer getSolidFillColor()
```

फ़िल रंग लौटाता है। केवल-पढ़ने योग्य java.lang.Integer।

**रिटर्न:**
java.lang.Integer
### getSolidFillSchemeColor() {#getSolidFillSchemeColor--}
```
public abstract int getSolidFillSchemeColor()
```

रंग योजना द्वारा निर्धारित फ़िल रंग प्राप्त करता है। [SchemeColor.NotDefined](../../com.aspose.slides/schemecolor\#NotDefined) मान दर्शाता है कि SolidFillColor (\#getSolidFillColor.getSolidFillColor) एक योजना रंग नहीं है। केवल-पढ़ने योग्य [SchemeColor](../../com.aspose.slides/schemecolor)।

**रिटर्न:**
int
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```

ग्रेडिएंट फ़िल फ़ॉर्मेट लौटाता है। केवल-पढ़ने योग्य [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)।

**रिटर्न:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```

पैटर्न फ़िल फ़ॉर्मेट लौटाता है। केवल-पढ़ने योग्य [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)।

**रिटर्न:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormatEffectiveData getPictureFillFormat()
```

चित्र फ़िल फ़ॉर्मेट लौटाता है। केवल-पढ़ने योग्य [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata)।

**रिटर्न:**
[IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```

निर्धारित करता है कि फ़िल को आकार के साथ घुमाया जाना चाहिए या नहीं। केवल-पढ़ने योग्य boolean।

**रिटर्न:**
boolean