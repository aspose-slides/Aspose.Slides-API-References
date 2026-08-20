---
title: LineFillFormat
second_title: Aspose.Slides for Java API संदर्भ
description: लाइन भराव के गुणों का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/linefillformat/
---
**विरासत:** 
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**सभी लागू इंटरफ़ेस:** 
[com.aspose.slides.ILineFillFormat](../../com.aspose.slides/ilinefillformat)
```
public final class LineFillFormat extends PVIObject implements ILineFillFormat
```

लाइन भराव के लिए गुणों का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | भरण प्रकार को प्राप्त करता है या सेट करता है। |
| [setFillType(byte value)](#setFillType-byte-) | भरण प्रकार को प्राप्त करता है या सेट करता है। |
| [getRotateWithShape()](#getRotateWithShape--) | निर्धारित करता है कि क्या भरण को आकार के साथ घुमा दिया जाना चाहिए। |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | निर्धारित करता है कि क्या भरण को आकार के साथ घुमा दिया जाना चाहिए। |
| [getSolidFillColor()](#getSolidFillColor--) | सॉलिड भरण का रंग वापस करता है। |
| [getGradientFormat()](#getGradientFormat--) | ग्रेडिएंट भरण स्वरूप वापस करता है। |
| [getPatternFormat()](#getPatternFormat--) | पैटर्न भरण स्वरूप वापस करता है। |
### getVersion() {#getVersion--}
```
public long getVersion()
```


संस्करण। केवल-पढ़ने योग्य लंबा।

**वापसी:**
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```


भरण प्रकार को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [FillType](../../com.aspose.slides/filltype)।

**वापसी:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```


भरण प्रकार को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [FillType](../../com.aspose.slides/filltype)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```


निर्धारित करता है कि क्या भरण को आकार के साथ घुमा दिया जाना चाहिए। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool)।

**वापसी:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```


निर्धारित करता है कि क्या भरण को आकार के साथ घुमा दिया जाना चाहिए। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```


सॉलिड भरण का रंग वापस करता है। केवल-पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat)।

**वापसी:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```


ग्रेडिएंट भरण स्वरूप वापस करता है। केवल-पढ़ने योग्य [IGradientFormat](../../com.aspose.slides/igradientformat)।

**वापसी:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```


पैटर्न भरण स्वरूप वापस करता है। केवल-पढ़ने योग्य [IPatternFormat](../../com.aspose.slides/ipatternformat)।

**वापसी:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)