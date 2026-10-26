---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides Android के लिए Java API रेफ़रेंस के माध्यम से
description: अपरिवर्तनीय ऑब्जेक्ट जिसमें प्रभावी पैटर्न भरने के गुण होते हैं।
type: docs
url: /hi/com.aspose.slides/ipatternformateffectivedata/
---```
public interface IPatternFormatEffectiveData
```

अपरिवर्तनीय ऑब्जेक्ट जिसमें प्रभावी पैटर्न भरने के गुण होते हैं।

--------------------

यह इंटरफ़ेस [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) और [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata) का एक हिस्सा के रूप में उपयोग किया जाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | पैटर्न शैली को लौटाता है। |
| [getForeColor()](#getForeColor--) | अग्रभूमि पैटर्न रंग को लौटाता है। |
| [getBackColor()](#getBackColor--) | पृष्ठभूमि पैटर्न रंग को लौटाता है। |
| [getTileIImage(Integer background, Integer foreground)](#getTileIImage-java.lang.Integer-java.lang.Integer-) | निर्दिष्ट रंगों के साथ पैटर्न भराव के लिए टाइल इमेज बनाता है। |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

पैटर्न शैली को लौटाता है। केवल-पढ़ने योग्य [PatternStyle](../../com.aspose.slides/patternstyle)।

**रिटर्न:**
byte
### getForeColor() {#getForeColor--}
```
public abstract Integer getForeColor()
```

अग्रभूमि पैटर्न रंग को लौटाता है। केवल-पढ़ने योग्य java.lang.Integer।

**रिटर्न:**
java.lang.Integer
### getBackColor() {#getBackColor--}
```
public abstract Integer getBackColor()
```

पृष्ठभूमि पैटर्न रंग को लौटाता है। केवल-पढ़ने योग्य java.lang.Integer।

**रिटर्न:**
java.lang.Integer
### getTileIImage(Integer background, Integer foreground) {#getTileIImage-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTileIImage(Integer background, Integer foreground)
```

निर्दिष्ट रंगों के साथ पैटर्न भराव के लिए टाइल इमेज बनाता है।

**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| background | java.lang.Integer | पैटर्न के लिए पृष्ठभूमि java.lang.Integer। |
| foreground | java.lang.Integer | पैटर्न के लिए अग्रभूमि java.lang.Integer। |

**रिटर्न:**
[IImage](../../com.aspose.slides/iimage) - Tile [IImage](../../com.aspose.slides/iimage).