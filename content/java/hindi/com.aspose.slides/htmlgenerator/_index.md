---
title: HtmlGenerator
second_title: Aspose.Slides जावा API संदर्भ
description: HTML जनरेटर।
type: docs
url: /hi/com.aspose.slides/htmlgenerator/
---
**विरासत:**  
java.lang.Object

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator)  
```
public final class HtmlGenerator implements IHtmlGenerator
```

Html जनरेटर।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | फ़ॉर्मेटेड HTML टेक्स्ट जोड़ता है। |
| [addHtml(char[] html)](#addHtml-char---) | फ़ॉर्मेटेड HTML टेक्स्ट जोड़ता है। |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | फ़ॉर्मेटेड HTML टेक्स्ट जोड़ता है। |
| [addText(String text)](#addText-java.lang.String-) | HTML फ़ाइलों में साधारण टेक्स्ट जोड़ता है, विशेष अक्षरों को HTML एंटिटी में बदलते हुए। |
| [addText(char[] text)](#addText-char---) | HTML फ़ाइलों में साधारण टेक्स्ट जोड़ता है, विशेष अक्षरों को HTML एंटिटी में बदलते हुए। |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | HTML फ़ाइलों में साधारण टेक्स्ट जोड़ता है, विशेष अक्षरों को HTML एंटिटी में बदलते हुए। |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | एट्रीब्यूट वैल्यू को क्वोट करता है और इसे html फ़ाइल में जोड़ता है। |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | एट्रीब्यूट वैल्यू को क्वोट करता है और इसे html फ़ाइल में जोड़ता है। |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | एट्रीब्यूट वैल्यू को क्वोट करता है और इसे html फ़ाइल में जोड़ता है। |
| [getSlideImageSize()](#getSlideImageSize--) | स्लाइड इमेज आकार लौटाता है। |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | एक इकाई लौटाता है जिसमें स्लाइड इमेज आकार निर्दिष्ट होता है। |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | स्लाइड इमेज आकार में निर्दिष्ट इकाई का CSS कोड लौटाता है। |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | पहले रेंडर किए गए स्लाइड का इंडेक्स लौटाता है या -1 यदि प्रथम स्लाइड रेंडर हो रही है। |
| [getSlideIndex()](#getSlideIndex--) | वर्तमान में रेंडर हो रहे स्लाइड का इंडेक्स लौटाता है। |
| [getNextSlideIndex()](#getNextSlideIndex--) | एक स्लाइड का इंडेक्स लौटाता है, जो वर्तमान स्लाइड के बाद रेंडर होगा या -1 यदि वर्तमान में अंतिम स्लाइड रेंडर हो रही है। |
### addHtml(String html) {#addHtml-java.lang.String-}
```
public final void addHtml(String html)
```


फ़ॉर्मेटेड HTML टेक्स्ट जोड़ता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| html | java.lang.String | जोड़ने के लिए टेक्स्ट। |

### addHtml(char[] html) {#addHtml-char---}
```
public final void addHtml(char[] html)
```


फ़ॉर्मेटेड HTML टेक्स्ट जोड़ता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| html | char[] | जोड़ने के लिए टेक्स्ट। |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public final void addHtml(char[] html, int startIndex, int length)
```


फ़ॉर्मेटेड HTML टेक्स्ट जोड़ता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| html | char[] | जोड़ने के लिए टेक्स्ट। |
| startIndex | int | जोड़ने वाले भाग का प्रारम्भ इंडेक्स। |
| length | int | जोड़ने वाले भाग की लंबाई। |

### addText(String text) {#addText-java.lang.String-}
```
public final void addText(String text)
```


HTML फ़ाइलों में साधारण टेक्स्ट जोड़ता है, विशेष अक्षरों को HTML एंटिटी में बदलते हुए। लाइन ब्रेक और व्हाइटस्पेस नहीं बदले जाते।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| text | java.lang.String | जोड़ने के लिए टेक्स्ट। |

### addText(char[] text) {#addText-char---}
```
public final void addText(char[] text)
```


HTML फ़ाइलों में साधारण टेक्स्ट जोड़ता है, विशेष अक्षरों को HTML एंटिटी में बदलते हुए। लाइन ब्रेक और व्हाइटस्पेस नहीं बदले जाते।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| text | char[] | जोड़ने के लिए टेक्स्ट। |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public final void addText(char[] text, int startIndex, int length)
```


HTML फ़ाइलों में साधारण टेक्स्ट जोड़ता है, विशेष अक्षरों को HTML एंटिटी में बदलते हुए। लाइन ब्रेक और व्हाइटस्पेस नहीं बदले जाते।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| text | char[] | जोड़ने के लिए टेक्स्ट। |
| startIndex | int | जोड़ने वाले भाग का प्रारम्भ इंडेक्स। |
| length | int | जोड़ने वाले भाग की लंबाई। |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public final void addAttributeValue(String value)
```


एट्रीब्यूट वैल्यू को क्वोट करता है और इसे html फ़ाइल में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | java.lang.String | एट्रीब्यूट वैल्यू स्ट्रिंग। |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public final void addAttributeValue(char[] value)
```


एट्रीब्यूट वैल्यू को क्वोट करता है और इसे html फ़ाइल में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | char[] | एट्रीब्यूट वैल्यू स्ट्रिंग। |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public final void addAttributeValue(char[] value, int startIndex, int length)
```


एट्रीब्यूट वैल्यू को क्वोट करता है और इसे html फ़ाइल में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | char[] | एट्रीब्यूट वैल्यू स्ट्रिंग। |
| startIndex | int | जोड़ने वाले भाग का प्रारम्भ इंडेक्स। |
| length | int | जोड़ने वाले भाग की लंबाई। |

### getSlideImageSize() {#getSlideImageSize--}
```
public final Dimension2D getSlideImageSize()
```


स्लाइड इमेज आकार लौटाता है। केवल-पढ़ने योग्य java.awt.geom.Dimension2D।

**रिटर्न्स:**
java.awt.geom.Dimension2D
### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public final int getSlideImageSizeUnit()
```


एक इकाई लौटाता है जिसमें स्लाइड इमेज आकार निर्दिष्ट होता है। केवल-पढ़ने योग्य [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit)।

**रिटर्न्स:**
int
### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public final String getSlideImageSizeUnitCode()
```


स्लाइड इमेज आकार में निर्दिष्ट इकाई का CSS कोड लौटाता है। केवल-पढ़ने योग्य String।

**रिटर्न्स:**
java.lang.String
### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public final int getPreviousSlideIndex()
```


पहले रेंडर किए गए स्लाइड का इंडेक्स लौटाता है या -1 यदि प्रथम स्लाइड रेंडर हो रही है। केवल-पढ़ने योग्य int।

**रिटर्न्स:**
int
### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```


वर्तमान में रेंडर हो रहे स्लाइड का इंडेक्स लौटाता है। केवल-पढ़ने योग्य int।

**रिटर्न्स:**
int
### getNextSlideIndex() {#getNextSlideIndex--}
```
public final int getNextSlideIndex()
```


एक स्लाइड का इंडेक्स लौटाता है, जो वर्तमान स्लाइड के बाद रेंडर होगा या -1 यदि वर्तमान में अंतिम स्लाइड रेंडर हो रही है। केवल-पढ़ने योग्य int।

**रिटर्न्स:**
int