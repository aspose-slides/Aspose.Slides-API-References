---
title: IMathBox
second_title: Aspose.Slides for Java API संदर्भ
description: गणितीय तत्व की तर्कसंगत बॉक्सिंग पैकेजिंग को निर्दिष्ट करता है।
type: docs
url: /hi/com.aspose.slides/imathbox/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBox extends IMathElement
```

गणितीय तत्व की तर्कसंगत बॉक्सिंग (पैकेजिंग) को निर्दिष्ट करता है। उदाहरण के लिए, एक बॉक्स्ड ऑब्जेक्ट को ऑपरेटर इम्यूलेटर के रूप में संरेखण बिंदु के साथ या बिना उपयोग किया जा सकता है, लाइन ब्रेक बिंदु के रूप में कार्य कर सकता है, या इस तरह समूहित किया जा सकता है कि उसके भीतर लाइन ब्रेक की अनुमति न हो। उदाहरण के लिए, "==" ऑपरेटर को लाइन ब्रेक को रोकने के लिए बॉक्स्ड किया जाना चाहिए।

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
> ```
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getOperatorEmulator()](#getOperatorEmulator--) | Operator Emulator. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Operator Emulator. |
| [getNoBreak()](#getNoBreak--) | No break. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | No break. |
| [getDifferential()](#getDifferential--) | Differential. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Differential. |
| [getAlignmentPoint()](#getAlignmentPoint--) | When true, this operator emulator serves as an alignment point; that is, designated alignment points in other equations can be aligned with it. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | When true, this operator emulator serves as an alignment point; that is, designated alignment points in other equations can be aligned with it. |
| [getExplicitBreak()](#getExplicitBreak--) | Explicit break specifies whether there is a line break at the start of the Box object, such that the line wraps at the start of the box object. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Explicit break specifies whether there is a line break at the start of the Box object, such that the line wraps at the start of the box object. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

आधार तर्क

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  IMathElement base = box.getBase();
>  ```

**परिणाम:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public abstract boolean getOperatorEmulator()
```

ऑपरेटर इम्यूलेटर। जब true हो, बॉक्स और उसकी सामग्री एकल ऑपरेटर की तरह व्यवहार करती है और ऑपरेटर की गुणधर्म विरासत में प्राप्त करती है। इसका अर्थ है, उदाहरण के लिए, कि यह अक्षर लाइन ब्रेक बिंदु के रूप में कार्य कर सकता है और अन्य ऑपरेटर्स के साथ संरेखित हो सकता है। ऑपरेटर इम्यूलेटर अक्सर तब उपयोग किए जाते हैं जब एक या अधिक ग्लिफ़ मिलकर एक ऑपरेटर बनाते हैं, जैसे '=='। डिफ़ॉल्ट मान: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**परिणाम:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public abstract void setOperatorEmulator(boolean value)
```

ऑपरेटर इम्यूलेटर। जब true हो, बॉक्स और उसकी सामग्री एकल ऑपरेटर की तरह व्यवहार करती है और ऑपरेटर की गुणधर्म विरासत में प्राप्त करती है। इसका अर्थ है, उदाहरण के लिए, कि यह अक्षर लाइन ब्रेक बिंदु के रूप में कार्य कर सकता है और अन्य ऑपरेटर्स के साथ संरेखित हो सकता है। ऑपरेटर इम्यूलेटर अक्सर तब उपयोग किए जाते हैं जब एक या अधिक ग्लिफ़ मिलकर एक ऑपरेटर बनाते हैं, जैसे '=='। डिफ़ॉल्ट मान: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public abstract boolean getNoBreak()
```

No break. This property specifies the "unbreakable" property on the object box. When true, no line breaks can occur within the box. This can be important for operator emulators that consist of more than one binary operator. When this element is not specified, breaks can occur inside box. Default: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**परिणाम:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public abstract void setNoBreak(boolean value)
```

No break. This property specifies the "unbreakable" property on the object box. When true, no line breaks can occur within the box. This can be important for operator emulators that consist of more than one binary operator. When this element is not specified, breaks can occur inside box. Default: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public abstract boolean getDifferential()
```

Differential. When true, the box acts as a differential (e.g., \\ud835\\udc51\\ud835\\udc65 in an integrand), and receives the appropriate horizontal spacing for the mathematical differential. Default: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**परिणाम:**
boolean
### setDifferential(boolean value) {#setDifferential-boolean-}
```
public abstract void setDifferential(boolean value)
```

Differential. When true, the box acts as a differential (e.g., \\ud835\\udc51\\ud835\\udc65 in an integrand), and receives the appropriate horizontal spacing for the mathematical differential. Default: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getAlignmentPoint() {#getAlignmentPoint--}
```
public abstract boolean getAlignmentPoint()
```

When true, this operator emulator serves as an alignment point; that is, designated alignment points in other equations can be aligned with it. Default: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**परिणाम:**
boolean
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public abstract void setAlignmentPoint(boolean value)
```

When true, this operator emulator serves as an alignment point; that is, designated alignment points in other equations can be aligned with it. Default: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getExplicitBreak() {#getExplicitBreak--}
```
public abstract byte getExplicitBreak()
```

Explicit break specifies whether there is a line break at the start of the Box object, such that the line wraps at the start of the box object. Specifies the number of the operator on the previous line of mathematical text which shall be used as the alignment point for the current line of mathematical text possible values: 1..255 Default: 0 (no explicit break)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**परिणाम:**
byte
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public abstract void setExplicitBreak(byte value)
```

Explicit break specifies whether there is a line break at the start of the Box object, such that the line wraps at the start of the box object. Specifies the number of the operator on the previous line of mathematical text which shall be used as the alignment point for the current line of mathematical text possible values: 1..255 Default: 0 (no explicit break)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |