---
title: IFillFormat
second_title: Aspose.Slides for Java API संदर्भ
description: फ़िल फ़ॉर्मेटिंग विकल्पों का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ifillformat/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormat extends IFillParamSource
```

फ़िल फ़ॉर्मेटिंग विकल्पों का प्रतिनिधित्व करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getFillType()](#getFillType--) | भरण के प्रकार को लौटाता है या सेट करता है। |
| [setFillType(byte value)](#setFillType-byte-) | भरण के प्रकार को लौटाता है या सेट करता है। |
| [getSolidFillColor()](#getSolidFillColor--) | भरण का रंग लौटाता है। |
| [getGradientFormat()](#getGradientFormat--) | ग्रेडिएंट भरण फ़ॉर्मेट लौटाता है। |
| [getPatternFormat()](#getPatternFormat--) | पैटर्न भरण फ़ॉर्मेट लौटाता है। |
| [getPictureFillFormat()](#getPictureFillFormat--) | चित्र भरण फ़ॉर्मेट लौटाता है। |
| [getRotateWithShape()](#getRotateWithShape--) | निर्धारित करता है कि क्या भरण को आकार के साथ घुमाया जाना चाहिए। |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | निर्धारित करता है कि क्या भरण को आकार के साथ घुमाया जाना चाहिए। |
| [getEffective()](#getEffective--) | विरासत लागू करके प्रभावी फ़िल फ़ॉर्मेटिंग डेटा प्राप्त करता है। |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


भरण के प्रकार को लौटाता है या सेट करता है। पढ़ें/लिखें [FillType](../../com.aspose.slides/filltype).

**रिटर्न:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```


भरण के प्रकार को लौटाता है या सेट करता है। पढ़ें/लिखें [FillType](../../com.aspose.slides/filltype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```


भरण का रंग लौटाता है। केवल पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat).

**रिटर्न:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```


ग्रेडिएंट भरण फ़ॉर्मेट लौटाता है। केवल पढ़ने योग्य [IGradientFormat](../../com.aspose.slides/igradientformat).

**रिटर्न:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```


पैटर्न भरण फ़ॉर्मेट लौटाता है। केवल पढ़ने योग्य [IPatternFormat](../../com.aspose.slides/ipatternformat).

**रिटर्न:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormat getPictureFillFormat()
```


चित्र भरण फ़ॉर्मेट लौटाता है। केवल पढ़ने योग्य [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**रिटर्न:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```


निर्धारित करता है कि क्या भरण को आकार के साथ घुमाया जाना चाहिए। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool).

**रिटर्न:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```


निर्धारित करता है कि क्या भरण को आकार के साथ घुमाया जाना चाहिए। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### getEffective() {#getEffective--}
```
public abstract IFillFormatEffectiveData getEffective()
```


विरासत लागू करके प्रभावी फ़िल फ़ॉर्मेटिंग डेटा प्राप्त करता है।

**रिटर्न:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - A [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).