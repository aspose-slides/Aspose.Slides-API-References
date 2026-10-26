---
title: HtmlGenerator
second_title: Android के लिए Aspose.Slides, Java API संदर्भ द्वारा
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

HTML जनरेटर।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | स्वरूपित HTML टेक्स्ट जोड़ता है। |
| [addHtml(char[] html)](#addHtml-char---) | स्वरूपित HTML टेक्स्ट जोड़ता है। |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | स्वरूपित HTML टेक्स्ट जोड़ता है। |
| [addText(String text)](#addText-java.lang.String-) | HTML फ़ाइलों में साधारण टेक्स्ट जोड़ता है, विशेष वर्णों को HTML एंटिटीज़ से बदलता है। |
| [addText(char[] text)](#addText-char---) | HTML फ़ाइलों में साधारण टेक्स्ट जोड़ता है, विशेष वर्णों को HTML एंटिटीज़ से बदलता है। |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | HTML फ़ाइलों में साधारण टेक्स्ट जोड़ता है, विशेष वर्णों को HTML एंटिटीज़ से बदलता है। |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | एट्रिब्यूट मान को उद्धरण चिह्नों में लेता है और HTML फ़ाइल में जोड़ता है। |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | एट्रिब्यूट मान को उद्धरण चिह्नों में लेता है और HTML फ़ाइल में जोड़ता है। |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | एट्रिब्यूट मान को उद्धरण चिह्नों में लेता है और HTML फ़ाइल में जोड़ता है। |
| [getSlideImageSize()](#getSlideImageSize--) | स्लाइड इमेज आकार लौटाता है। |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | स्लाइड इमेज आकार निर्दिष्ट करने वाली इकाई लौटाता है। |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | स्लाइड इमेज आकार निर्दिष्ट करने वाली इकाई का CSS कोड लौटाता है। |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | पहले रेंडर की गई स्लाइड का इंडेक्स लौटाता है या यदि पहली स्लाइड रेंडर हो रही है तो -1 लौटाता है। |
| [getSlideIndex()](#getSlideIndex--) | वर्तमान में रेंडर हो रही स्लाइड का इंडेक्स लौटाता है। |
| [getNextSlideIndex()](#getNextSlideIndex--) | वर्तमान स्लाइड के बाद रेंडर होने वाली स्लाइड का इंडेक्स लौटाता है या यदि वर्तमान में अंतिम स्लाइड रेंडर हो रही है तो -1 लौटाता है। |

### addHtml(String html) {#addHtml-java.lang.String-}
```
public final void addHtml(String html)
```

स्वरूपित HTML टेक्स्ट जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| html | java.lang.String | जोड़ने के लिए टेक्स्ट। |

### addHtml(char[] html) {#addHtml-char---}
```
public final void addHtml(char[] html)
```

स्वरूपित HTML टेक्स्ट जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| html | char[] | जोड़ने के लिए टेक्स्ट। |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public final void addHtml(char[] html, int startIndex, int length)
```

स्वरूपित HTML टेक्स्ट जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| html | char[] | जोड़ने के लिए टेक्स्ट। |
| startIndex | int | जोड़ने वाले भाग का प्रारम्भिक इंडेक्स। |
| length | int | जोड़ने वाले भाग की लंबाई। |

### addText(String text) {#addText-java.lang.String-}
```
public final void addText(String text)
```

HTML फ़ाइलों में साधारण टेक्स्ट जोड़ता है, विशेष वर्णों को HTML एंटिटीज़ से बदलता है। लाइन ब्रेक और व्हाइटस्पेस बदले नहीं जाते।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | जोड़ने के लिए टेक्स्ट। |

### addText(char[] text) {#addText-char---}
```
public final void addText(char[] text)
```

HTML फ़ाइलों में साधारण टेक्स्ट जोड़ता है, विशेष वर्णों को HTML एंटिटीज़ से बदलता है। लाइन ब्रेक और व्हाइटस्पेस बदले नहीं जाते।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | char[] | जोड़ने के लिए टेक्स्ट। |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public final void addText(char[] text, int startIndex, int length)
```

HTML फ़ाइलों में साधारण टेक्स्ट जोड़ता है, विशेष वर्णों को HTML एंटिटीज़ से बदलता है। लाइन ब्रेक और व्हाइटस्पेस बदले नहीं जाते।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | char[] | जोड़ने के लिए टेक्स्ट। |
| startIndex | int | जोड़ने वाले भाग का प्रारम्भिक इंडेक्स। |
| length | int | जोड़ने वाले भाग की लंबाई। |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public final void addAttributeValue(String value)
```

एट्रिब्यूट मान को उद्धरण चिह्नों में लेता है और HTML फ़ाइल में जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String | एट्रिब्यूट मान स्ट्रिंग। |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public final void addAttributeValue(char[] value)
```

एट्रिब्यूट मान को उद्धरण चिह्नों में लेता है और HTML फ़ाइल में जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | char[] | एट्रिब्यूट मान स्ट्रिंग। |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public final void addAttributeValue(char[] value, int startIndex, int length)
```

एट्रिब्यूट मान को उद्धरण चिह्नों में लेता है और HTML फ़ाइल में जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | char[] | एट्रिब्यूट मान स्ट्रिंग। |
| startIndex | int | जोड़ने वाले भाग का प्रारम्भिक इंडेक्स। |
| length | int | जोड़ने वाले भाग की लंबाई। |

### getSlideImageSize() {#getSlideImageSize--}
```
public final SizeF getSlideImageSize()
```

स्लाइड इमेज आकार लौटाता है। केवल-पढ़ने योग्य [SizeF](../../com.aspose.slides.android/sizef)।

**रिटर्न:**  
[SizeF](../../com.aspose.slides.android/sizef)

### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public final int getSlideImageSizeUnit()
```

स्लाइड इमेज आकार निर्दिष्ट करने वाली इकाई लौटाता है। केवल-पढ़ने योग्य [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit)।

**रिटर्न:**  
int

### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public final String getSlideImageSizeUnitCode()
```

स्लाइड इमेज आकार निर्दिष्ट करने वाली इकाई का CSS कोड लौटाता है। केवल-पढ़ने योग्य String।

**रिटर्न:**  
java.lang.String

### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public final int getPreviousSlideIndex()
```

पहले रेंडर की गई स्लाइड का इंडेक्स लौटाता है या यदि पहली स्लाइड रेंडर हो रही है तो -1 लौटाता है। केवल-पढ़ने योग्य int।

**रिटर्न:**  
int

### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```

वर्तमान में रेंडर हो रही स्लाइड का इंडेक्स लौटाता है। केवल-पढ़ने योग्य int।

**रिटर्न:**  
int

### getNextSlideIndex() {#getNextSlideIndex--}
```
public final int getNextSlideIndex()
```

वर्तमान स्लाइड के बाद रेंडर होने वाली स्लाइड का इंडेक्स लौटाता है या यदि वर्तमान में अंतिम स्लाइड रेंडर हो रही है तो -1 लौटाता है। केवल-पढ़ने योग्य int।

**रिटर्न:**  
int