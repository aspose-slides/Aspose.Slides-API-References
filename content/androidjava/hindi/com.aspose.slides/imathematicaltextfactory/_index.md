---
title: IMathematicalTextFactory
second_title: Aspose.Slides for Android via Java API Reference
description: MathematicalText तत्व बनाने की अनुमति देता है
type: docs
url: /hi/com.aspose.slides/imathematicaltextfactory/
---```
public interface IMathematicalTextFactory
```

MathematicalText तत्व बनाने की अनुमति देता है

--------------------

COM संगतता के लिये
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | Create empty mathematical text element |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | Create mathematical text element with the specified value |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Create empty mathematical text element with the specified value |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Create empty mathematical text element with the specified value and formatting properties |
### createMathematicalText() {#createMathematicalText--}
```
public abstract IMathematicalText createMathematicalText()
```

खाली गणितीय टेक्स्ट तत्व बनाएं

**वापसी:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public abstract IMathematicalText createMathematicalText(char mathSymbol)
```

निर्दिष्ट मान के साथ गणितीय टेक्स्ट तत्व बनाएं

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| mathSymbol | char | एकल चिन्ह जिसे टेक्स्ट मान के रूप में उपयोग किया जाएगा |

**वापसी:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public abstract IMathematicalText createMathematicalText(String mathText)
```

निर्दिष्ट मान के साथ खाली गणितीय टेक्स्ट तत्व बनाएं

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| mathText | java.lang.String | टेक्स्ट मान |

**वापसी:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public abstract IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```

निर्दिष्ट मान और स्वरूपण गुणों के साथ खाली गणितीय टेक्स्ट तत्व बनाएं

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| mathText | java.lang.String | टेक्स्ट मान |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | टेक्स्ट स्वरूप सेटिंग्स |

**वापसी:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text