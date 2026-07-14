---
title: ISlideSize
second_title: Aspose.Slides for Android via Java API Reference
description: Represents the size and orientation of a slide.
type: docs
url: /hi/com.aspose.slides/islidesize/
---```
public interface ISlideSize
```

एक स्लाइड के आकार और अभिविन्यास को दर्शाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getSize()](#getSize--) | स्लाइड के आयाम बिंदुओं में प्राप्त करता है। |
| [getType()](#getType--) | स्लाइड आकार प्रकार प्राप्त करता है। |
| [getOrientation()](#getOrientation--) | स्लाइड अभिविन्यास प्राप्त करता है या सेट करता है। |
| [setOrientation(int value)](#setOrientation-int-) | स्लाइड अभिविन्यास प्राप्त करता है या सेट करता है। |
| [setSize(int type, int scaleType)](#setSize-int-int-) | प्रकार द्वारा स्लाइड आकार सेट करता है और मौजूदा सामग्री को स्केल करता है। |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | स्लाइड आयाम स्पष्ट रूप से सेट करता है और मौजूदा सामग्री को स्केल करता है। |
### getSize() {#getSize--}
```
public abstract SizeF getSize()
```

स्लाइड के आयाम बिंदुओं में प्राप्त करता है।

--------------------

एक नया मान असाइन करने से \#getType.getType प्रॉपर्टी [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) पर रीसेट हो जाता है और \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) सेट होता है।

**रिटर्न मान:**
[SizeF](../../com.aspose.slides.android/sizef)
### getType() {#getType--}
```
public abstract int getType()
```

स्लाइड आकार प्रकार प्राप्त करता है।

--------------------

[SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) को छोड़कर कोई भी मान असाइन करने से पूर्वनिर्धारित आयामों के अनुसार \#getSize.getSize समायोजित होता है, जबकि वर्तमान \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) बरकरार रहता है।

**रिटर्न मान:**
int
### getOrientation() {#getOrientation--}
```
public abstract int getOrientation()
```

स्लाइड अभिविन्यास प्राप्त करता है या सेट करता है।

--------------------

इस मान को बदलने से स्लाइड की चौड़ाई और ऊँचाई आपस में बदल जाती हैं।

**रिटर्न मान:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public abstract void setOrientation(int value)
```

स्लाइड अभिविन्यास प्राप्त करता है या सेट करता है।

--------------------

इस मान को बदलने से स्लाइड की चौड़ाई और ऊँचाई आपस में बदल जाती हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public abstract void setSize(int type, int scaleType)
```

प्रकार द्वारा स्लाइड आकार सेट करता है और मौजूदा सामग्री को स्केल करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | int | लागू करने के लिए पूर्वनिर्धारित स्लाइड आकार। |
| scaleType | int | उपयोग करने के लिए सामग्री स्केलिंग मोड। |

--------------------

[SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) को छोड़कर कोई भी मान असाइन करने से चयनित प्रकार के आधार पर \#getSize.getSize समायोजित होता है, जबकि \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) बरकरार रहता है। |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public abstract void setSize(float width, float height, int scaleType)
```

स्लाइड आयाम स्पष्ट रूप से सेट करता है और मौजूदा सामग्री को स्केल करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| width | float | नए स्लाइड की चौड़ाई, बिंदुओं में। |
| height | float | नए स्लाइड की ऊँचाई, बिंदुओं में। |
| scaleType | int | उपयोग करने के लिए सामग्री स्केलिंग मोड। |

--------------------

यह \#getType.getType प्रॉपर्टी को [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) पर रीसेट करता है और \{\#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) को सेट करता है। |