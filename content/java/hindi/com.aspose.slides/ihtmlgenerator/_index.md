---
title: IHtmlGenerator
second_title: Aspose.Slides for Java API Reference
description: Html generator.
type: docs
url: /hi/com.aspose.slides/ihtmlgenerator/
---```
public interface IHtmlGenerator
```

HTML जेनरेटर।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | फ़ॉर्मेटेड HTML टेक्स्ट जोड़ता है। |
| [addHtml(char[] html)](#addHtml-char---) | फ़ॉर्मेटेड HTML टेक्स्ट जोड़ता है। |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | फ़ॉर्मेटेड HTML टेक्स्ट जोड़ता है। |
| [addText(String text)](#addText-java.lang.String-) | HTML फ़ाइलों में साधारण टेक्स्ट जोड़ता है, विशेष अक्षरों को HTML एंटिटीज़ से बदलता है। |
| [addText(char[] text)](#addText-char---) | HTML फ़ाइलों में साधारण टेक्स्ट जोड़ता है, विशेष अक्षरों को HTML एंटिटीज़ से बदलता है। |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | HTML फ़ाइलों में साधारण टेक्स्ट जोड़ता है, विशेष अक्षरों को HTML एंटिटीज़ से बदलता है। |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | गुणधर्म (attribute) मान को उद्धरण में लेता है और HTML फ़ाइल में जोड़ता है। |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | गुणधर्म (attribute) मान को उद्धरण में लेता है और HTML फ़ाइल में जोड़ता है। |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | गुणधर्म (attribute) मान को उद्धरण में लेता है और HTML फ़ाइल में जोड़ता है। |
| [getSlideImageSize()](#getSlideImageSize--) | स्लाइड इमेज आकार लौटाता है। |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | वह इकाई लौटाता है जिसमें स्लाइड इमेज आकार निर्दिष्ट किया गया है। |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | उस इकाई का CSS कोड लौटाता है जिसमें स्लाइड इमेज आकार निर्दिष्ट किया गया है। |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | पिछले रेंडर किए गए स्लाइड का इंडेक्स या -1 यदि यह पहला स्लाइड है, लौटाता है। |
| [getSlideIndex()](#getSlideIndex--) | वर्तमान में रेंडर हो रहे स्लाइड का इंडेक्स लौटाता है। |
| [getNextSlideIndex()](#getNextSlideIndex--) | वह स्लाइड इंडेक्स लौटाता है जो वर्तमान स्लाइड के बाद रेंडर होगा, या -1 यदि वर्तमान स्लाइड आखिरी है। |

### addHtml(String html) {#addHtml-java.lang.String-}
```
public abstract void addHtml(String html)
```

फ़ॉर्मेटेड HTML टेक्स्ट जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| html | java.lang.String | जोड़ने के लिये टेक्स्ट। |

### addHtml(char[] html) {#addHtml-char---}
```
public abstract void addHtml(char[] html)
```

फ़ॉर्मेटेड HTML टेक्स्ट जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| html | char[] | जोड़ने के लिये टेक्स्ट। |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public abstract void addHtml(char[] html, int startIndex, int length)
```

फ़ॉर्मेटेड HTML टेक्स्ट जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| html | char[] | जोड़ने के लिये टेक्स्ट। |
| startIndex | int | जोड़ने के लिये भाग का प्रारम्भिक इंडेक्स। |
| length | int | जोड़ने के लिये भाग की लंबाई। |

### addText(String text) {#addText-java.lang.String-}
```
public abstract void addText(String text)
```

HTML फ़ाइलों में साधारण टेक्स्ट जोड़ता है, विशेष अक्षरों को HTML एंटिटीज़ से बदलता है। लाइनब्रेक और सफ़ेद स्थान नहीं बदले जाते।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | जोड़ने के लिये टेक्स्ट। |

### addText(char[] text) {#addText-char---}
```
public abstract void addText(char[] text)
```

HTML फ़ाइलों में साधारण टेक्स्ट जोड़ता है, विशेष अक्षरों को HTML एंटिटीज़ से बदलता है। लाइनब्रेक और सफ़ेद स्थान नहीं बदले जाते।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | char[] | जोड़ने के लिये टेक्स्ट। |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public abstract void addText(char[] text, int startIndex, int length)
```

HTML फ़ाइलों में साधारण टेक्स्ट जोड़ता है, विशेष अक्षरों को HTML एंटिटीज़ से बदलता है। लाइनब्रेक और सफ़ेद स्थान नहीं बदले जाते।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | char[] | जोड़ने के लिये टेक्स्ट। |
| startIndex | int | जोड़ने के लिये भाग का प्रारम्भिक इंडेक्स। |
| length | int | जोड़ने के लिये भाग की लंबाई। |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public abstract void addAttributeValue(String value)
```

गुणधर्म मान को उद्धरण में लेता है और HTML फ़ाइल में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String | गुणधर्म मान स्ट्रिंग। |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public abstract void addAttributeValue(char[] value)
```

गुणधर्म मान को उद्धरण में लेता है और HTML फ़ाइल में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | char[] | गुणधर्म मान स्ट्रिंग। |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public abstract void addAttributeValue(char[] value, int startIndex, int length)
```

गुणधर्म मान को उद्धरण में लेता है और HTML फ़ाइल में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | char[] | गुणधर्म मान स्ट्रिंग। |
| startIndex | int | जोड़ने के लिये भाग का प्रारम्भिक इंडेक्स। |
| length | int | जोड़ने के लिये भाग की लंबाई। |

### getSlideImageSize() {#getSlideImageSize--}
```
public abstract Dimension2D getSlideImageSize()
```

स्लाइड इमेज आकार लौटाता है। केवल-पढ़ने योग्य java.awt.geom.Dimension2D।

**रिटर्न:**
java.awt.geom.Dimension2D

### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public abstract int getSlideImageSizeUnit()
```

स्लाइड इमेज आकार निर्दिष्ट करने वाली इकाई लौटाता है। केवल-पढ़ने योग्य [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit)।

**रिटर्न:**
int

### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public abstract String getSlideImageSizeUnitCode()
```

स्लाइड इमेज आकार निर्दिष्ट करने वाली इकाई का CSS कोड लौटाता है। केवल-पढ़ने योग्य String।

**रिटर्न:**
java.lang.String

### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public abstract int getPreviousSlideIndex()
```

पहले रेंडर किए गए स्लाइड का इंडेक्स या -1 यदि यह पहला स्लाइड है, लौटाता है। केवल-पढ़ने योग्य int।

**रिटर्न:**
int

### getSlideIndex() {#getSlideIndex--}
```
public abstract int getSlideIndex()
```

वर्तमान में रेंडर हो रहे स्लाइड का इंडेक्स लौटाता है। केवल-पढ़ने योग्य int।

**रिटर्न:**
int

### getNextSlideIndex() {#getNextSlideIndex--}
```
public abstract int getNextSlideIndex()
```

वर्तमान स्लाइड के बाद रेंडर होने वाले स्लाइड का इंडेक्स या -1 यदि यह आखिरी स्लाइड है, लौटाता है। केवल-पढ़ने योग्य int।

**रिटर्न:**
int