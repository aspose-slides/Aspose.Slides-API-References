---
title: IPatternFormat
second_title: Aspose.Slides for Android via Java API Reference
description: एक आकार को भरने के लिए पैटर्न का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ipatternformat/
---```
public interface IPatternFormat
```

एक आकार को भरने के लिए पैटर्न का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | पैटर्न शैली को प्राप्त करता है या सेट करता है। |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | पैटर्न शैली को प्राप्त करता है या सेट करता है। |
| [getForeColor()](#getForeColor--) | फ़ोरग्राउंड पैटर्न रंग को प्राप्त करता है। |
| [getBackColor()](#getBackColor--) | बैकग्राउंड पैटर्न रंग को प्राप्त करता है। |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | निर्दिष्ट रंगों के साथ पैटर्न फिल के लिए टाइल इमेज बनाता है। |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | पैटर्न फिल के लिए टाइल इमेज बनाता है। |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```


पैटर्न शैली को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [PatternStyle](../../com.aspose.slides/patternstyle).

**रिटर्न:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```


पैटर्न शैली को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [PatternStyle](../../com.aspose.slides/patternstyle).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public abstract IColorFormat getForeColor()
```


फ़ोरग्राउंड पैटर्न रंग को प्राप्त करता है। केवल-पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat).

**रिटर्न:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public abstract IColorFormat getBackColor()
```


बैकग्राउंड पैटर्न रंग को प्राप्त करता है। केवल-पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat).

**रिटर्न:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTile(Integer background, Integer foreground)
```


निर्दिष्ट रंगों के साथ पैटर्न फिल के लिए टाइल इमेज बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| background | java.lang.Integer | पैटर्न के लिए बैकग्राउंड java.lang.Integer। |
| foreground | java.lang.Integer | पैटर्न के लिए फ़ोरग्राउंड java.lang.Integer। |

**रिटर्न:**
[IImage](../../com.aspose.slides/iimage) - टाइल android.graphics.Bitmap.
### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public abstract IImage getTile(Integer styleColor)
```


पैटर्न फिल के लिए टाइल इमेज बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| styleColor | java.lang.Integer | डिफ़ॉल्ट java.lang.Integer, जो ShapeEx के StyleEx ऑब्जेक्ट में परिभाषित है। फिल के रंग इस पर निर्भर कर सकते हैं। |

**रिटर्न:**
[IImage](../../com.aspose.slides/iimage) - टाइल android.graphics.Bitmap.