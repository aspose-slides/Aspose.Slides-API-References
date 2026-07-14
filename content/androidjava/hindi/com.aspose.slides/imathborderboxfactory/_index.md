---
title: IMathBorderBoxFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math border box
type: docs
url: /hi/com.aspose.slides/imathborderboxfactory/
---```
public interface IMathBorderBoxFactory
```

गणित बॉर्डर बॉक्स बनाने की अनुमति देता है

--------------------

COM संगतता के लिए

## विधाएँ

| विधि | विवरण |
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
| element | [IMathElement](../../com.aspose.slides/imathelement) | बॉर्डर बॉक्स लागू करने के लिए गणित तत्व |

**रिटर्न मान:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - नया बॉर्डर बॉक्स तत्व

### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

तत्व पर लागू करके एक गणित बॉर्डर बॉक्स बनाता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | बॉर्डर बॉक्स लागू करने के लिए गणित तत्व |
| hideTop | boolean | ऊपरी किनारा छुपाएँ |
| hideBottom | boolean | निचला किनारा छुपाएँ |
| hideLeft | boolean | बायाँ किनारा छुपाएँ |
| hideRight | boolean | दायाँ किनारा छुपाएँ |
| strikethroughHorizontal | boolean | बॉर्डर बॉक्स क्षैतिज स्ट्राइकथ्रू |
| strikethroughVertical | boolean | बॉर्डर बॉक्स ऊर्ध्वाधर स्ट्राइकथ्रू |
| strikethroughBottomLeftToTopRight | boolean | बॉर्डर बॉक्स बायां-निचला से दायां-ऊपर स्ट्राइकथ्रू |
| strikethroughTopLeftToBottomRight | boolean | बॉर्डर बॉक्स बायां-ऊपर से दायां-निचला स्ट्राइकथ्रू |

**रिटर्न मान:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - नया बॉर्डर बॉक्स तत्व