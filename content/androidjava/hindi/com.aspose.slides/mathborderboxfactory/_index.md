---
title: MathBorderBoxFactory
second_title: Android के लिए Aspose.Slides, Java API संदर्भ के माध्यम से
description: गणित बॉर्डर बॉक्स बनाने की अनुमति देता है
type: docs
url: /hi/com.aspose.slides/mathborderboxfactory/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IMathBorderBoxFactory](../../com.aspose.slides/imathborderboxfactory)
```
public class MathBorderBoxFactory implements IMathBorderBoxFactory
```

गणित बॉर्डर बॉक्स बनाने की अनुमति देता है

--------------------

COM संगतता के लिए
## कन्स्ट्रक्टर्स

| Constructor | Description |
| --- | --- |
| [MathBorderBoxFactory()](#MathBorderBoxFactory--) |  |
## मेथड्स

| Method | Description |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | तत्व पर लागू करके गणित बॉर्डर बॉक्स बनाता है |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | तत्व पर लागू करके गणित बॉर्डर बॉक्स बनाता है |
### MathBorderBoxFactory() {#MathBorderBoxFactory--}
```
public MathBorderBoxFactory()
```

### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element)
```

तत्व पर लागू करके गणित बॉर्डर बॉक्स बनाता है

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | बॉर्डर बॉक्स लागू करने के लिए गणित तत्व |
**रिटर्न:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - नया बॉर्डर बॉक्स तत्व
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

तत्व पर लागू करके गणित बॉर्डर बॉक्स बनाता है

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | बॉर्डर बॉक्स लागू करने के लिए गणित तत्व |
| hideTop | boolean | शीर्ष किनारा छुपाएँ |
| hideBottom | boolean | निचला किनारा छुपाएँ |
| hideLeft | boolean | बायाँ किनारा छुपाएँ |
| hideRight | boolean | दायाँ किनारा छुपाएँ |
| strikethroughHorizontal | boolean | बॉर्डर बॉक्स क्षैतिज स्ट्राइकथ्रू |
| strikethroughVertical | boolean | बॉर्डर बॉक्स लंबवत स्ट्राइकथ्रू |
| strikethroughBottomLeftToTopRight | boolean | बॉर्डर बॉक्स निचला-बायाँ से ऊपर-दायाँ स्ट्राइकथ्रू |
| strikethroughTopLeftToBottomRight | boolean | बॉर्डर बॉक्स ऊपर-बायाँ से निचला-दायाँ स्ट्राइकथ्रू |
**रिटर्न:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - नया बॉर्डर बॉक्स तत्व