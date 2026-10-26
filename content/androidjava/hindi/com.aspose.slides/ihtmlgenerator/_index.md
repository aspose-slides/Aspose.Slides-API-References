---
title: IHtmlGenerator
second_title: Aspose.Slides for Android via Java API Reference
description: Html generator.
type: docs
url: /hi/com.aspose.slides/ihtmlgenerator/
---```
public interface IHtmlGenerator
```

HTML जनरेटर।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | फ़ॉर्मेटेड HTML टेक्स्ट जोड़ता है। |
| [addHtml(char[] html)](#addHtml-char---) | फ़ॉर्मेटेड HTML टेक्स्ट जोड़ता है। |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | फ़ॉर्मेटेड HTML टेक्स्ट जोड़ता है। |
| [addText(String text)](#addText-java.lang.String-) | HTML फ़ाइलों में साधारण टेक्स्ट जोड़ता है, विशेष वर्णों को HTML एंटिटी के साथ बदलता है। |
| [addText(char[] text)](#addText-char---) | HTML फ़ाइलों में साधारण टेक्स्ट जोड़ता है, विशेष वर्णों को HTML एंटिटी के साथ बदलता है। |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | HTML फ़ाइलों में साधारण टेक्स्ट जोड़ता है, विशेष वर्णों को HTML एंटिटी के साथ बदलता है। |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | एट्रीब्यूट वैल्यू को कोट करता है और इसे HTML फ़ाइल में जोड़ता है। |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | एट्रीब्यूट वैल्यू को कोट करता है और इसे HTML फ़ाइल में जोड़ता है। |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | एट्रीब्यूट वैल्यू को कोट करता है और इसे HTML फ़ाइल में जोड़ता है। |
| [getSlideImageSize()](#getSlideImageSize--) | स्लाइड इमेज आकार लौटाता है। |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | वह इकाई लौटाता है जिसमें स्लाइड इमेज आकार निर्दिष्ट किया गया है। |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | वह CSS कोड लौटाता है जो इकाई में स्लाइड इमेज आकार को निर्दिष्ट करता है। |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | पहले रेंडर किए गए स्लाइड का इंडेक्स लौटाता है या -1 यदि पहला स्लाइड रेंडर हो रहा है। |
| [getSlideIndex()](#getSlideIndex--) | वर्तमान में रेंडर हो रहे स्लाइड का इंडेक्स लौटाता है। |
| [getNextSlideIndex()](#getNextSlideIndex--) | वर्तमान स्लाइड के बाद रेंडर होने वाले स्लाइड का इंडेक्स लौटाता है या -1 यदि वर्तमान में आखिरी स्लाइड रेंडर हो रहा है। |

### addHtml(String html) {#addHtml-java.lang.String-}
```
public abstract void addHtml(String html)
```

फ़ॉर्मेटेड HTML टेक्स्ट जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| html | java.lang.String | जोड़ने के लिए टेक्स्ट। |

### addHtml(char[] html) {#addHtml-char---}
```
public abstract void addHtml(char[] html)
```

फ़ॉर्मेटेड HTML टेक्स्ट जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| html | char[] | जोड़ने के लिए टेक्स्ट। |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public abstract void addHtml(char[] html, int startIndex, int length)
```

फ़ॉर्मेटेड HTML टेक्स्ट जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| html | char[] | जोड़ने के लिए टेक्स्ट। |
| startIndex | int | जोड़ने के भाग का प्रारंभिक इंडेक्स। |
| length | int | जोड़ने के भाग की लंबाई। |

### addText(String text) {#addText-java.lang.String-}
```
public abstract void addText(String text)
```

HTML फ़ाइलों में साधारण टेक्स्ट जोड़ता है, विशेष वर्णों को HTML एंटिटी के साथ बदलता है। लाइनब्रेक और व्हाइटस्पेस को नहीं बदला जाता।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | जोड़ने के लिए टेक्स्ट। |

### addText(char[] text) {#addText-char---}
```
public abstract void addText(char[] text)
```

HTML फ़ाइलों में साधारण टेक्स्ट जोड़ता है, विशेष वर्णों को HTML एंटिटी के साथ बदलता है। लाइनब्रेक और व्हाइटस्पेस को नहीं बदला जाता।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | char[] | जोड़ने के लिए टेक्स्ट। |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public abstract void addText(char[] text, int startIndex, int length)
```

HTML फ़ाइलों में साधारण टेक्स्ट जोड़ता है, विशेष वर्णों को HTML एंटिटी के साथ बदलता है। लाइनब्रेक और व्हाइटस्पेस को नहीं बदला जाता।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | char[] | जोड़ने के लिए टेक्स्ट। |
| startIndex | int | जोड़ने के भाग का प्रारंभिक इंडेक्स। |
| length | int | जोड़ने के भाग की लंबाई। |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public abstract void addAttributeValue(String value)
```

एट्रीब्यूट वैल्यू को कोट करता है और इसे HTML फ़ाइल में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String | एट्रीब्यूट वैल्यू स्ट्रिंग। |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public abstract void addAttributeValue(char[] value)
```

एट्रीब्यूट वैल्यू को कोट करता है और इसे HTML फ़ाइल में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | char[] | एट्रीब्यूट वैल्यू स्ट्रिंग। |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public abstract void addAttributeValue(char[] value, int startIndex, int length)
```

एट्रीब्यूट वैल्यू को कोट करता है और इसे HTML फ़ाइल में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | char[] | एट्रीब्यूट वैल्यू स्ट्रिंग। |
| startIndex | int | जोड़ने के भाग का प्रारंभिक इंडेक्स। |
| length | int | जोड़ने के भाग की लंबाई। |

### getSlideImageSize() {#getSlideImageSize--}
```
public abstract SizeF getSlideImageSize()
```

स्लाइड इमेज आकार लौटाता है। केवल-पढ़ने योग्य [SizeF](../../com.aspose.slides.android/sizef)।

**रिटर्न:**
[SizeF](../../com.aspose.slides.android/sizef)

### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public abstract int getSlideImageSizeUnit()
```

वह इकाई लौटाता है जिसमें स्लाइड इमेज आकार निर्दिष्ट किया गया है। केवल-पढ़ने योग्य [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit)।

**रिटर्न:**
int

### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public abstract String getSlideImageSizeUnitCode()
```

वह CSS कोड लौटाता है जो इकाई में स्लाइड इमेज आकार को निर्दिष्ट करता है। केवल-पढ़ने योग्य String।

**रिटर्न:**
java.lang.String

### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public abstract int getPreviousSlideIndex()
```

पहले रेंडर किए गए स्लाइड का इंडेक्स लौटाता है या -1 यदि पहला स्लाइड रेंडर हो रहा है। केवल-पढ़ने योग्य int।

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

वर्तमान स्लाइड के बाद रेंडर होने वाले स्लाइड का इंडेक्स लौटाता है या -1 यदि वर्तमान में आखिरी स्लाइड रेंडर हो रहा है। केवल-पढ़ने योग्य int।

**रिटर्न:**
int