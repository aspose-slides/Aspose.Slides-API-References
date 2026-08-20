---
title: IMathBorderBoxFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a math border box
type: docs
url: /hi/com.aspose.slides/imathborderboxfactory/
---```
public interface IMathBorderBoxFactory
```

गणित बॉर्डर बॉक्स बनाने की अनुमति देता है

--------------------

COM संगतता के लिए
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | तत्व पर लागू करके एक गणित बॉर्डर बॉक्स बनाता है |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | तत्व पर लागू करके एक गणित बॉर्डर बॉक्स बनाता है |
### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element)
```

तत्व पर लागू करके एक गणित बॉर्डर बॉक्स बनाता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | बॉर्डर बॉक्स लागू करने के लिए गणितीय तत्व |

**रिटर्न्स:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - नया बॉर्डर बॉक्स तत्व
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

तत्व पर लागू करके एक गणित बॉर्डर बॉक्स बनाता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | बॉर्डर बॉक्स लागू करने के लिए गणितीय तत्व |
| hideTop | boolean | ऊपरी किनारा छिपाएँ |
| hideBottom | boolean | निचला किनारा छिपाएँ |
| hideLeft | boolean | बायाँ किनारा छिपाएँ |
| hideRight | boolean | दायाँ किनारा छिपाएँ |
| strikethroughHorizontal | boolean | बॉर्डर बॉक्स क्षैतिज स्ट्राइकथ्रू |
| strikethroughVertical | boolean | बॉर्डर बॉक्स लंबवत स्ट्राइकथ्रू |
| strikethroughBottomLeftToTopRight | boolean | बॉटम-लेफ्ट से टॉप-राइट तक बॉर्डर बॉक्स स्ट्राइकथ्रू |
| strikethroughTopLeftToBottomRight | boolean | टॉप-लेफ्ट से बॉटम-राइट तक बॉर्डर बॉक्स स्ट्राइकथ्रू |

**रिटर्न्स:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - नया बॉर्डर बॉक्स तत्व