---
title: FormatFactory
second_title: Aspose.Slides Android के लिए, Java API रेफ़रेंस के माध्यम से
description: COM इंटरफ़ेस के माध्यम से फ़ॉर्मेट बनाना संभव बनाता है।
type: docs
url: /hi/com.aspose.slides/formatfactory/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IFormatFactory](../../com.aspose.slides/iformatfactory)
```
public class FormatFactory implements IFormatFactory
```

COM इंटरफ़ेस के माध्यम से फ़ॉर्मैट बनाने की अनुमति देता है.
## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [FormatFactory()](#FormatFactory--) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getInstance()](#getInstance--) | फ़ॉर्मैट फ़ैक्टरी स्थिर उदाहरण। |
| [createPortionFormat()](#createPortionFormat--) | नया [IPortionFormat](../../com.aspose.slides/iportionformat) बनाता है। |
| [createParagraphFormat()](#createParagraphFormat--) | नया [IParagraphFormat](../../com.aspose.slides/iparagraphformat) बनाता है। |
| [createTextFrameFormat()](#createTextFrameFormat--) | नया [ITextFrameFormat](../../com.aspose.slides/itextframeformat) बनाता है। |
### FormatFactory() {#FormatFactory--}
```
public FormatFactory()
```


### getInstance() {#getInstance--}
```
public static FormatFactory getInstance()
```


फ़ॉर्मैट फ़ैक्टरी स्थिर उदाहरण। केवल-पढ़ने योग्य [FormatFactory](../../com.aspose.slides/formatfactory)।

**वापसी:**
[FormatFactory](../../com.aspose.slides/formatfactory)
### createPortionFormat() {#createPortionFormat--}
```
public final IPortionFormat createPortionFormat()
```


नया [IPortionFormat](../../com.aspose.slides/iportionformat) बनाता है।

**वापसी:**
[IPortionFormat](../../com.aspose.slides/iportionformat) - नया पोर्शन फ़ॉर्मैट।
### createParagraphFormat() {#createParagraphFormat--}
```
public final IParagraphFormat createParagraphFormat()
```


नया [IParagraphFormat](../../com.aspose.slides/iparagraphformat) बनाता है।

**वापसी:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - नया पैराग्राफ फ़ॉर्मैट।
### createTextFrameFormat() {#createTextFrameFormat--}
```
public final ITextFrameFormat createTextFrameFormat()
```


नया [ITextFrameFormat](../../com.aspose.slides/itextframeformat) बनाता है।

**वापसी:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat) - नया टेक्स्ट फ्रेम फ़ॉर्मैट।