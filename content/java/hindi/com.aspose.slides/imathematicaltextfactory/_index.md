---
title: IMathematicalTextFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a MathematicalText element
type: docs
url: /hi/com.aspose.slides/imathematicaltextfactory/
---```
public interface IMathematicalTextFactory
```

MathematicalText तत्व बनाने की अनुमति देता है

--------------------

COM संगतता के लिए
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | खाली गणितीय टेक्स्ट तत्व बनाएँ |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | निर्दिष्ट मान के साथ गणितीय टेक्स्ट तत्व बनाएँ |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | निर्दिष्ट मान के साथ खाली गणितीय टेक्स्ट तत्व बनाएँ |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | निर्दिष्ट मान और स्वरूपण गुणों के साथ खाली गणितीय टेक्स्ट तत्व बनाएँ |
### createMathematicalText() {#createMathematicalText--}
```
public abstract IMathematicalText createMathematicalText()
```

खाली गणितीय टेक्स्ट तत्व बनाएँ

**वापसी:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - नया Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public abstract IMathematicalText createMathematicalText(char mathSymbol)
```

निर्दिष्ट मान के साथ गणितीय टेक्स्ट तत्व बनाएँ

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| mathSymbol | char | पाठ मान के रूप में उपयोग करने के लिए एकल प्रतीक |

**वापसी:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - नया Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public abstract IMathematicalText createMathematicalText(String mathText)
```

निर्दिष्ट मान के साथ खाली गणितीय टेक्स्ट तत्व बनाएँ

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| mathText | java.lang.String | टेक्स्ट मान |

**वापसी:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - नया Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public abstract IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```

निर्दिष्ट मान और स्वरूपण गुणों के साथ खाली गणितीय टेक्स्ट तत्व बनाएँ

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| mathText | java.lang.String | टेक्स्ट मान |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | टेक्स्ट स्वरूप सेटिंग्स |

**वापसी:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - नया Mathematical Text