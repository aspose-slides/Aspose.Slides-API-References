---
title: SlideSize
second_title: Aspose.Slides for Java API संदर्भ
description: एक स्लाइड के आकार और अभिविन्यास का प्रतिनिधित्व करता है।
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

एक स्लाइड का आकार और अभिविन्यास दर्शाता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getSize()](#getSize--) | स्लाइड के आयाम बिंदुओं में प्राप्त करता है। |
| [getType()](#getType--) | स्लाइड आकार प्रकार प्राप्त करता है। |
| [getOrientation()](#getOrientation--) | स्लाइड अभिविन्यास प्राप्त या सेट करता है। |
| [setOrientation(int value)](#setOrientation-int-) | स्लाइड अभिविन्यास प्राप्त या सेट करता है। |
| [setSize(int type, int scaleType)](#setSize-int-int-) | प्रकार द्वारा स्लाइड आकार सेट करता है और मौजूदा सामग्री को स्केल करता है। |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | स्लाइड आयाम स्पष्ट रूप से सेट करता है और मौजूदा सामग्री को स्केल करता है। |
### getSize() {#getSize--}
```
public final Dimension2D getSize()
```

स्लाइड के आयाम बिंदुओं में प्राप्त करता है।

--------------------

नया मान असाइन करने से \#getType.getType प्रॉपर्टी [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) पर रीसेट हो जाती है और \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) सेट हो जाता है।

**वापसी:**
java.awt.geom.Dimension2D
### getType() {#getType--}
```
public final int getType()
```

स्लाइड आकार प्रकार प्राप्त करता है।

--------------------

[SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) के अलावा कोई भी मान असाइन करने से \#getSize.getSize को पूर्वनिर्धारित आयामों के अनुसार समायोजित किया जाता है, जबकि वर्तमान \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) बरकरार रहता है।

**वापसी:**
int
### getOrientation() {#getOrientation--}
```
public final int getOrientation()
```

स्लाइड अभिविन्यास प्राप्त या सेट करता है।

--------------------

इस मान को बदलने से स्लाइड की चौड़ाई और ऊँचाई आपस में बदल जाती हैं।

**वापसी:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public final void setOrientation(int value)
```

स्लाइड अभिविन्यास प्राप्त या सेट करता है।

--------------------

इस मान को बदलने से स्लाइड की चौड़ाई और ऊँचाई आपस में बदल जाती हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public final void setSize(int type, int scaleType)
```

प्रकार द्वारा स्लाइड आकार सेट करता है और मौजूदा सामग्री को स्केल करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | int | लागू करने के लिए पूर्वनिर्धारित स्लाइड आकार। |
| scaleType | int | उपयोग करने के लिए सामग्री स्केलिंग मोड। |

--------------------

[SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) के अलावा कोई भी मान असाइन करने से चयनित प्रकार के आधार पर \#getSize.getSize समायोजित किया जाता है, जबकि \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) बरकरार रहता है। |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public final void setSize(float width, float height, int scaleType)
```

स्लाइड आयाम स्पष्ट रूप से सेट करता है और मौजूदा सामग्री को स्केल करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| width | float | नए स्लाइड की चौड़ाई, बिंदुओं में। |
| height | float | नए स्लाइड की ऊँचाई, बिंदुओं में। |
| scaleType | int | उपयोग करने के लिए सामग्री स्केलिंग मोड। |

--------------------

यह \#getType.getType प्रॉपर्टी को [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) पर रीसेट करता है और \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) सेट करता है। |