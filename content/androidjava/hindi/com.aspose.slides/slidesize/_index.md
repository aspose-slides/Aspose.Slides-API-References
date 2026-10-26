---
title: SlideSize
second_title: Aspose.Slides for Android के लिये Java API संदर्भ
description: स्लाइड के आकार और अभिविन्यास का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/slidesize/
---
**विरासत:**
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ISlideSize](../../com.aspose.slides/islidesize)
```
public class SlideSize extends DomObject<Presentation> implements ISlideSize
```

एक स्लाइड के आकार और अभिविन्यास का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getSize()](#getSize--) | स्लाइड के आयाम बिंदुओं में प्राप्त करता है। |
| [getType()](#getType--) | स्लाइड आकार प्रकार प्राप्त करता है। |
| [getOrientation()](#getOrientation--) | स्लाइड अभिविन्यास प्राप्त या सेट करता है। |
| [setOrientation(int value)](#setOrientation-int-) | स्लाइड अभिविन्यास प्राप्त या सेट करता है। |
| [setSize(int type, int scaleType)](#setSize-int-int-) | स्लाइड आकार प्रकार द्वारा सेट करता है और मौजूदा सामग्री को स्केल करता है। |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | स्लाइड आयाम स्पष्ट रूप से सेट करता है और मौजूदा सामग्री को स्केल करता है। |
### getSize() {#getSize--}
```
public final SizeF getSize()
```


स्लाइड के आयाम बिंदुओं में प्राप्त करता है।

--------------------

नई मान असाइन करने से \#getType.getType प्रॉपर्टी [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) पर रीसेट हो जाती है और \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) सेट हो जाता है।

**रिटर्न:**
[SizeF](../../com.aspose.slides.android/sizef)
### getType() {#getType--}
```
public final int getType()
```


स्लाइड आकार प्रकार प्राप्त करता है।

--------------------

[SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) के अलावा कोई भी मान असाइन करने से \#getSize.getSize पूर्वनिर्धारित आयामों के अनुसार समायोजित हो जाता है, जबकि वर्तमान \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) बरकरार रहता है।

**रिटर्न:**
int
### getOrientation() {#getOrientation--}
```
public final int getOrientation()
```


स्लाइड अभिविन्यास प्राप्त या सेट करता है।

--------------------

इस मान को बदलने से स्लाइड की चौड़ाई और ऊँचाई आपस में बदल जाती है।

**रिटर्न:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public final void setOrientation(int value)
```


स्लाइड अभिविन्यास प्राप्त या सेट करता है।

--------------------

इस मान को बदलने से स्लाइड की चौड़ाई और ऊँचाई आपस में बदल जाती है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public final void setSize(int type, int scaleType)
```


स्लाइड आकार प्रकार द्वारा सेट करता है और मौजूदा सामग्री को स्केल करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | int | लागू करने के लिए पूर्वनिर्धारित स्लाइड आकार। |
| scaleType | int | उपयोग करने के लिए सामग्री स्केलिंग मोड। |

--------------------

[SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) के अलावा कोई भी मान असाइन करने से \#getSize.getSize चयनित प्रकार के आधार पर समायोजित हो जाता है, जबकि \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) संरक्षित रहता है। |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public final void setSize(float width, float height, int scaleType)
```


स्लाइड आयाम स्पष्ट रूप से सेट करता है और मौजूदा सामग्री को स्केल करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| width | float | बिंदुओं में नया स्लाइड चौड़ाई। |
| height | float | बिंदुओं में नया स्लाइड ऊँचाई। |
| scaleType | int | उपयोग करने के लिए सामग्री स्केलिंग मोड। |

--------------------

यह \#getType.getType प्रॉपर्टी को [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) पर रीसेट करता है और \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) सेट करता है। |