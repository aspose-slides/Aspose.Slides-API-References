---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective pattern filling properties.
type: docs
url: /hi/com.aspose.slides/ipatternformateffectivedata/
---```
public interface IPatternFormatEffectiveData
```

एक अपरिवर्तनीय ऑब्जेक्ट जो प्रभावी पैटर्न भरने की विशेषताएँ रखता है।

--------------------

यह इंटरफ़ेस [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) और [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata) का हिस्सा के रूप में उपयोग किया जाता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | पैटर्न शैली लौटाता है। |
| [getForeColor()](#getForeColor--) | अग्रभूमि पैटर्न रंग लौटाता है। |
| [getBackColor()](#getBackColor--) | पृष्ठभूमि पैटर्न रंग लौटाता है। |
| [getTileIImage(Color background, Color foreground)](#getTileIImage-java.awt.Color-java.awt.Color-) | निर्दिष्ट रंगों के साथ पैटर्न फ़िल के लिए टाइल इमेज बनाता है। |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```


पैटर्न शैली लौटाता है। केवल पढ़ने योग्य [PatternStyle](../../com.aspose.slides/patternstyle)।

**वापसी:**
byte
### getForeColor() {#getForeColor--}
```
public abstract Color getForeColor()
```


अग्रभूमि पैटर्न रंग लौटाता है। केवल पढ़ने योग्य java.awt.Color।

**वापसी:**
java.awt.Color
### getBackColor() {#getBackColor--}
```
public abstract Color getBackColor()
```


पृष्ठभूमि पैटर्न रंग लौटाता है। केवल पढ़ने योग्य java.awt.Color।

**वापसी:**
java.awt.Color
### getTileIImage(Color background, Color foreground) {#getTileIImage-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTileIImage(Color background, Color foreground)
```


निर्दिष्ट रंगों के साथ पैटर्न फ़िल के लिए टाइल इमेज बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| background | java.awt.Color | पैटर्न के लिए पृष्ठभूमि java.awt.Color। |
| foreground | java.awt.Color | पैटर्न के लिए अग्रभूमि java.awt.Color। |

**वापसी:**
[IImage](../../com.aspose.slides/iimage) - Tile [IImage](../../com.aspose.slides/iimage).