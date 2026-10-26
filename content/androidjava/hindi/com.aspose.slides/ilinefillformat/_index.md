---
title: ILineFillFormat
second_title: Aspose.Slides for Android के लिए जावा API रेफ़रेंस
description: लाइन भरने के लिए गुणों का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ilinefillformat/
---
**सभी लागू किए गए इंटरफ़ेस:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormat extends IFillParamSource
```

लाइन भरने के लिए गुणों का प्रतिनिधित्व करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getFillType()](#getFillType--) | फ़िल प्रकार को लौटाता है या सेट करता है। |
| [setFillType(byte value)](#setFillType-byte-) | फ़िल प्रकार को लौटाता है या सेट करता है। |
| [getSolidFillColor()](#getSolidFillColor--) | एक ठोस फ़िल का रंग लौटाता है। |
| [getGradientFormat()](#getGradientFormat--) | ग्रेडिएंट फ़िल प्रारूप लौटाता है। |
| [getPatternFormat()](#getPatternFormat--) | पैटर्न फ़िल प्रारूप लौटाता है। |
| [getRotateWithShape()](#getRotateWithShape--) | निर्धारित करता है कि फ़िल को आकार के साथ घुमाया जाना चाहिए या नहीं। |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | निर्धारित करता है कि फ़िल को आकार के साथ घुमाया जाना चाहिए या नहीं। |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


फ़िल प्रकार को लौटाता है या सेट करता है। पढ़ें/लिखें [FillType](../../com.aspose.slides/filltype).

**वापसी:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```


फ़िल प्रकार को लौटाता है या सेट करता है। पढ़ें/लिखें [FillType](../../com.aspose.slides/filltype).

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```


एक ठोस फ़िल का रंग लौटाता है। केवल-पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat).

**वापसी:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```


ग्रेडिएंट फ़िल प्रारूप लौटाता है। केवल-पढ़ने योग्य [IGradientFormat](../../com.aspose.slides/igradientformat).

**वापसी:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```


पैटर्न फ़िल प्रारूप लौटाता है। केवल-पढ़ने योग्य [IPatternFormat](../../com.aspose.slides/ipatternformat).

**वापसी:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```


निर्धारित करता है कि फ़िल को आकार के साथ घुमाया जाना चाहिए या नहीं। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool).

**वापसी:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```


निर्धारित करता है कि फ़िल को आकार के साथ घुमाया जाना चाहिए या नहीं। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool).

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |