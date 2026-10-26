---
title: LineFillFormat
second_title: Aspose.Slides for Android के माध्यम से Java API संदर्भ
description: रेखाओं के भराव की विशेषताओं का प्रतिनिधित्व करता है।
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

रेखाओं के भराव के गुणों को दर्शाता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | भराव प्रकार को प्राप्त करता है या सेट करता है। |
| [setFillType(byte value)](#setFillType-byte-) | भराव प्रकार को प्राप्त करता है या सेट करता है। |
| [getRotateWithShape()](#getRotateWithShape--) | निर्धारित करता है कि क्या भराव को आकार के साथ घुमाया जाना चाहिए। |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | निर्धारित करता है कि क्या भराव को आकार के साथ घुमाया जाना चाहिए। |
| [getSolidFillColor()](#getSolidFillColor--) | एक ठोस भराव का रंग लौटाता है। |
| [getGradientFormat()](#getGradientFormat--) | ग्रेडिएंट भराव प्रारूप लौटाता है। |
| [getPatternFormat()](#getPatternFormat--) | पैटर्न भराव प्रारूप लौटाता है। |
### getVersion() {#getVersion--}
```
public long getVersion()
```

संस्करण। केवल-पढ़ने योग्य लोंग।

**वापसी:**  
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```

भराव प्रकार को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [FillType](../../com.aspose.slides/filltype)।

**वापसी:**  
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```

भराव प्रकार को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [FillType](../../com.aspose.slides/filltype)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```

निर्धारित करता है कि क्या भराव को आकार के साथ घुमाया जाना चाहिए। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**वापसी:**  
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```

निर्धारित करता है कि क्या भराव को आकार के साथ घुमाया जाना चाहिए। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```

एक ठोस भराव का रंग लौटाता है। केवल-पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat)।

**वापसी:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```

ग्रेडिएंट भराव प्रारूप लौटाता है। केवल-पढ़ने योग्य [IGradientFormat](../../com.aspose.slides/igradientformat)।

**वापसी:**  
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```

पैटर्न भराव प्रारूप लौटाता है। केवल-पढ़ने योग्य [IPatternFormat](../../com.aspose.slides/ipatternformat)।

**वापसी:**  
[IPatternFormat](../../com.aspose.slides/ipatternformat)