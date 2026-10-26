---
title: IPatternFormat
second_title: Aspose.Slides for Java API Reference
description: एक आकार को भरने के लिए पैटर्न का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ipatternformat/
---```
public interface IPatternFormat
```

एक आकार को भरने के लिए पैटर्न का प्रतिनिधित्व करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | पैटर्न शैली को लौटाता है या सेट करता है। |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | पैटर्न शैली को लौटाता है या सेट करता है। |
| [getForeColor()](#getForeColor--) | फ़ोरग्राउंड पैटर्न रंग को लौटाता है। |
| [getBackColor()](#getBackColor--) | बैकग्राउंड पैटर्न रंग को लौटाता है। |
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | निर्दिष्ट रंगों के साथ पैटर्न फ़िल के लिए टाइल इमेज बनाता है। |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | पैटर्न फ़िल के लिए टाइल इमेज बनाता है। |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```


पैटर्न शैली को लौटाता है या सेट करता है। पढ़ें/लिखें [PatternStyle](../../com.aspose.slides/patternstyle)।

**रिटर्न:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```


पैटर्न शैली को लौटाता है या सेट करता है। पढ़ें/लिखें [PatternStyle](../../com.aspose.slides/patternstyle).

**परामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public abstract IColorFormat getForeColor()
```


फ़ोरग्राउंड पैटर्न रंग को लौटाता है। केवल पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat)।

**रिटर्न:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public abstract IColorFormat getBackColor()
```


बैकग्राउंड पैटर्न रंग को लौटाता है। केवल पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat)।

**रिटर्न:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTile(Color background, Color foreground)
```


निर्दिष्ट रंगों के साथ पैटर्न फ़िल के लिए टाइल इमेज बनाता है।

**परामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| background | java.awt.Color | पैटर्न के लिए बैकग्राउंड java.awt.Color। |
| foreground | java.awt.Color | पैटर्न के लिए फ़ोरग्राउंड java.awt.Color। |

**रिटर्न:**
[IImage](../../com.aspose.slides/iimage) - Tile java.awt.image.BufferedImage.
### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public abstract IImage getTile(Color styleColor)
```


पैटर्न फ़िल के लिए टाइल इमेज बनाता है।

**परामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| styleColor | java.awt.Color | डिफ़ॉल्ट java.awt.Color, ShapeEx के StyleEx ऑब्जेक्ट में परिभाषित। Fill के रंग इस पर निर्भर हो सकते हैं। |

**रिटर्न:**
[IImage](../../com.aspose.slides/iimage) - Tile java.awt.image.BufferedImage.