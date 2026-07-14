---
title: PatternFormat
second_title: जावा API रेफ़रेंस के माध्यम से एंड्रॉइड के लिए Aspose.Slides
description: एक आकार को भरने के लिए पैटर्न का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/patternformat/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IPatternFormat](../../com.aspose.slides/ipatternformat)
```
public final class PatternFormat extends PVIObject implements IPatternFormat
```

एक आकार को भरने के लिए पैटर्न को दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPatternStyle()](#getPatternStyle--) | पैटर्न शैली को प्राप्त करता है या सेट करता है। |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | पैटर्न शैली को प्राप्त करता है या सेट करता है। |
| [getForeColor()](#getForeColor--) | फ़ोरग्राउंड पैटर्न रंग को प्राप्त करता है। |
| [getBackColor()](#getBackColor--) | बैकग्राउंड पैटर्न रंग को प्राप्त करता है। |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | निर्दिष्ट रंगों के साथ पैटर्न फ़िल के लिए टाइल छवि बनाता है। |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | पैटर्न फ़िल के लिए टाइल छवि बनाता है। |
### getVersion() {#getVersion--}
```
public long getVersion()
```


संस्करण। केवल पढ़ने योग्य लंबा।

**वापसी:**
long
### getPatternStyle() {#getPatternStyle--}
```
public final byte getPatternStyle()
```


पैटर्न शैली को प्राप्त करता है या सेट करता है। पढ़ने/लेखने योग्य [PatternStyle](../../com.aspose.slides/patternstyle)।

**वापसी:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public final void setPatternStyle(byte value)
```


पैटर्न शैली को प्राप्त करता है या सेट करता है। पढ़ने/लेखने योग्य [PatternStyle](../../com.aspose.slides/patternstyle)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public final IColorFormat getForeColor()
```


फ़ोरग्राउंड पैटर्न रंग को प्राप्त करता है। केवल पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat)।

**वापसी:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```


बैकग्राउंड पैटर्न रंग को प्राप्त करता है। केवल पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat)।

**वापसी:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public final IImage getTile(Integer background, Integer foreground)
```


निर्दिष्ट रंगों के साथ पैटर्न फ़िल के लिए टाइल छवि बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| background | java.lang.Integer | पैटर्न के लिए बैकग्राउंड java.lang.Integer। |
| foreground | java.lang.Integer | पैटर्न के लिए फ़ोरग्राउंड java.lang.Integer। |

**वापसी:**
[IImage](../../com.aspose.slides/iimage) - Tile [IImage](../../com.aspose.slides/iimage).
### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public final IImage getTile(Integer styleColor)
```


पैटर्न फ़िल के लिए टाइल छवि बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| styleColor | java.lang.Integer | डिफ़ॉल्ट java.lang.Integer |

**वापसी:**
[IImage](../../com.aspose.slides/iimage) *- Tile [IImage](../../com.aspose.slides/iimage)*.