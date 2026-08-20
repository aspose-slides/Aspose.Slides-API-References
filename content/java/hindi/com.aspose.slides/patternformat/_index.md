---
title: PatternFormat
second_title: Aspose.Slides के लिए Java API संदर्भ
description: एक आकार को भरने के लिए पैटर्न का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/patternformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IPatternFormat](../../com.aspose.slides/ipatternformat)
```
public final class PatternFormat extends PVIObject implements IPatternFormat
```

एक आकार को भरने के लिए पैटर्न का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPatternStyle()](#getPatternStyle--) | पैटर्न शैली को प्राप्त करता है या सेट करता है। |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | पैटर्न शैली को प्राप्त करता है या सेट करता है। |
| [getForeColor()](#getForeColor--) | फ़ोरग्राउंड पैटर्न रंग को लौटाता है। |
| [getBackColor()](#getBackColor--) | बैकग्राउंड पैटर्न रंग को लौटाता है। |
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | निर्दिष्ट रंगों के साथ पैटर्न फिल के लिए टाइल छवि बनाता है। |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | पैटर्न फिल के लिए टाइल छवि बनाता है। |
### getVersion() {#getVersion--}
```
public long getVersion()
```

संस्करण। केवल-पढ़ने योग्य long.

**रिटर्न:**
long
### getPatternStyle() {#getPatternStyle--}
```
public final byte getPatternStyle()
```

पैटर्न शैली को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [PatternStyle](../../com.aspose.slides/patternstyle)।

**रिटर्न:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public final void setPatternStyle(byte value)
```

पैटर्न शैली को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [PatternStyle](../../com.aspose.slides/patternstyle)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### getForeColor() {#getForeColor--}
```
public final IColorFormat getForeColor()
```

फ़ोरग्राउंड पैटर्न रंग को लौटाता है। केवल-पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat)।

**रिटर्न:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```

बैकग्राउंड पैटर्न रंग को लौटाता है। केवल-पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat)।

**रिटर्न:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public final IImage getTile(Color background, Color foreground)
```

निर्दिष्ट रंगों के साथ पैटर्न फिल के लिए टाइल छवि बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| background | java.awt.Color | पैटर्न के लिए बैकग्राउंड java.awt.Color। |
| foreground | java.awt.Color | पैटर्न के लिए फ़ोरग्राउंड java.awt.Color। |

**रिटर्न:**
[IImage](../../com.aspose.slides/iimage) - टाइल [IImage](../../com.aspose.slides/iimage)।
### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public final IImage getTile(Color styleColor)
```

पैटर्न फिल के लिए टाइल छवि बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| styleColor | java.awt.Color | डिफ़ॉल्ट java.awt.Color। |

**रिटर्न:**
[IImage](../../com.aspose.slides/iimage) - टाइल [IImage](../../com.aspose.slides/iimage)।