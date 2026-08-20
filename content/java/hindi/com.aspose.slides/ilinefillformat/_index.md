---
title: ILineFillFormat
second_title: Aspose.Slides for Java API संदर्भ
description: रेखाओं के भराव के गुण दर्शाता है।
type: docs
url: /hi/com.aspose.slides/ilinefillformat/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormat extends IFillParamSource
```

लाइन भरने के लिए गुण प्रस्तुत करता है।
## विधियां

| मेथड | विवरण |
| --- | --- |
| [getFillType()](#getFillType--) | फ़िल प्रकार को रिटर्न या सेट करता है। |
| [setFillType(byte value)](#setFillType-byte-) | फ़िल प्रकार को रिटर्न या सेट करता है। |
| [getSolidFillColor()](#getSolidFillColor--) | ठोस फ़िल का रंग रिटर्न करता है। |
| [getGradientFormat()](#getGradientFormat--) | ग्रेडिएंट फ़िल फ़ॉर्मेट रिटर्न करता है। |
| [getPatternFormat()](#getPatternFormat--) | पैटर्न फ़िल फ़ॉर्मेट रिटर्न करता है। |
| [getRotateWithShape()](#getRotateWithShape--) | निर्धारित करता है कि फ़िल को आकृति के साथ घुमाया जाए या नहीं। |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | निर्धारित करता है कि फ़िल को आकृति के साथ घुमाया जाए या नहीं। |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


फ़िल प्रकार को रिटर्न या सेट करता है। पढ़ने/लिखने योग्य [FillType](../../com.aspose.slides/filltype).

**रिटर्न:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```


फ़िल प्रकार को रिटर्न या सेट करता है। पढ़ने/लिखने योग्य [FillType](../../com.aspose.slides/filltype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```


ठोस फ़िल का रंग रिटर्न करता है। केवल पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat).

**रिटर्न:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```


ग्रेडिएंट फ़िल फ़ॉर्मेट रिटर्न करता है। केवल पढ़ने योग्य [IGradientFormat](../../com.aspose.slides/igradientformat).

**रिटर्न:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```


पैटर्न फ़िल फ़ॉर्मेट रिटर्न करता है। केवल पढ़ने योग्य [IPatternFormat](../../com.aspose.slides/ipatternformat).

**रिटर्न:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```


निर्धारित करता है कि फ़िल को आकृति के साथ घुमाया जाए या नहीं। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool).

**रिटर्न:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```


निर्धारित करता है कि फ़िल को आकृति के साथ घुमाया जाए या नहीं। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |