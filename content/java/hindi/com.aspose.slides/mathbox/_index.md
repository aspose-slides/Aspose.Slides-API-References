---
title: MathBox
second_title: Aspose.Slides for Java API संदर्भ
description: गणितीय तत्व के तार्किक बॉक्सिंग पैकेजिंग को निर्दिष्ट करता है।
type: docs
url: /hi/com.aspose.slides/mathbox/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**All Implemented Interfaces:**  
[com.aspose.slides.IMathBox](../../com.aspose.slides/imathbox), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathBox extends MathElementBase implements IMathBox, IHasControlCharacterProperties
```

गणितीय तत्व के तार्किक बॉक्सिंग (पैकेजिंग) को निर्दिष्ट करता है। उदाहरण के लिए, एक बॉक्स्ड वस्तु ऑपरेटर इम्यूलेटर के रूप में काम कर सकती है, चाहे उसमें संरेखण बिंदु हो या न हो, लाईन ब्रेक बिंदु के रूप में कार्य कर सकती है, या इसे इस प्रकार समूहित किया जा सकता है कि बॉक्स के भीतर लाइन ब्रेक की अनुमति न हो। उदाहरण के लिए, "==" ऑपरेटर को लाइन ब्रेक को रोकने के लिए बॉक्स्ड होना चाहिए।

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [MathBox(IMathElement element)](#MathBox-com.aspose.slides.IMathElement-) | निर्दिष्ट तत्व को तर्क के रूप में उपयोग करके MathBox को प्रारम्भ करता है |

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getBase()](#getBase--) | Base तर्क |
| [getOperatorEmulator()](#getOperatorEmulator--) | Operator Emulator. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Operator Emulator. |
| [getNoBreak()](#getNoBreak--) | No break यह गुण वस्तु बॉक्स पर "unbreakable" गुण को निर्दिष्ट करता है। |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | No break यह गुण वस्तु बॉक्स पर "unbreakable" गुण को निर्दिष्ट करता है। |
| [getDifferential()](#getDifferential--) | Differential जब true हो, बॉक्स एक डिफरेंशियल के रूप में कार्य करता है (उदाहरण के लिए, \\ud835\\udc51\\ud835\\udc65 एक इंटेग्रैंड में), और गणितीय डिफरेंशियल के लिए उपयुक्त क्षैतिज स्पेसिंग प्राप्त करता है। |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Differential जब true हो, बॉक्स एक डिफरेंशियल के रूप में कार्य करता है (उदाहरण के लिए, \\ud835\\udc51\\ud835\\udc65 एक इंटेग्रैंड में), और गणितीय डिफरेंशियल के लिए उपयुक्त क्षैतिज स्पेसिंग प्राप्त करता है। |
| [getAlignmentPoint()](#getAlignmentPoint--) | जब true हो, यह ऑपरेटर इम्यूलेटर एक संरेखण बिंदु के रूप में कार्य करता है; अर्थात्, अन्य समीकरणों में निर्धारित संरेखण बिंदुओं को इसके साथ संरेखित किया जा सकता है। |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | जब true हो, यह ऑपरेटर इम्यूलेटर एक संरेखण बिंदु के रूप में कार्य करता है; अर्थात्, अन्य समीकरणों में निर्धारित संरेखण बिंदुओं को इसके साथ संरेखित किया जा सकता है। |
| [getExplicitBreak()](#getExplicitBreak--) | Explicit break यह निर्धारित करता है कि बॉक्स वस्तु की शुरुआत में लाइन ब्रेक है या नहीं, जिससे लाइन बॉक्स वस्तु की शुरुआत पर रैप हो। |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Explicit break यह निर्धारित करता है कि बॉक्स वस्तु की शुरुआत में लाइन ब्रेक है या नहीं, जिससे लाइन बॉक्स वस्तु की शुरुआत पर रैप हो। |
| [getChildren()](#getChildren--) | बच्चों के तत्व प्राप्त करें |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |

### MathBox(IMathElement element) {#MathBox-com.aspose.slides.IMathElement-}
```
public MathBox(IMathElement element)
```

निर्दिष्ट तत्व को तर्क के रूप में उपयोग करके MathBox को प्रारम्भ करता है

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```

**परिमाण:**  
| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | बॉक्स लागू किए जाने वाला बेस तत्व। null भी हो सकता है। |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Base तर्क

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  IMathElement base = box.getBase();
> ```

**रिटर्न:**  
[IMathElement](../../com.aspose.slides/imathelement)

### getOperatorEmulator() {#getOperatorEmulator--}
```
public final boolean getOperatorEmulator()
```

Operator Emulator. जब true हो, बॉक्स और उसकी सामग्री एक एकल ऑपरेटर की तरह व्यवहार करती हैं और ऑपरेटर की विशेषताओं को विरासत में लेती हैं। इसका अर्थ है कि, उदाहरण के लिए, यह अक्षर लाइन ब्रेक के बिंदु के रूप में कार्य कर सकता है और अन्य ऑपरेटरों के साथ संरेखित हो सकता है। ऑपरेटर इम्यूलेटर अक्सर तब उपयोग किए जाते हैं जब एक या अधिक glyphs मिलकर एक ऑपरेटर बनाते हैं, जैसे '=='. डिफ़ॉल्ट मान: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**रिटर्न:**  
boolean  
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public final void setOperatorEmulator(boolean value)
```

Operator Emulator. जब true हो, बॉक्स और उसकी सामग्री एक एकल ऑपरेटर की तरह व्यवहार करती हैं और ऑपरेटर की विशेषताओं को विरासत में लेती हैं। इसका अर्थ है कि, उदाहरण के लिए, यह अक्षर लाइन ब्रेक के बिंदु के रूप में कार्य कर सकता है और अन्य ऑपरेटरों के साथ संरेखित हो सकता है। ऑपरेटर इम्यूलेटर अक्सर तब उपयोग किए जाते हैं जब एक या अधिक glyphs मिलकर एक ऑपरेटर बनाते हैं, जैसे '=='. डिफ़ॉल्ट मान: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**परिमाण:**  
| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public final boolean getNoBreak()
```

No break यह गुण वस्तु बॉक्स पर "unbreakable" गुण को निर्दिष्ट करता है। जब true हो, बॉक्स के भीतर कोई लाइन ब्रेक नहीं हो सकता। यह उन ऑपरेटर इम्यूलेटर्स के लिए महत्वपूर्ण हो सकता है जो एक से अधिक बाइनरी ऑपरेटर से बने होते हैं। जब यह तत्व निर्दिष्ट नहीं किया जाता, तो बॉक्स के अंदर ब्रेक हो सकते हैं। डिफ़ॉल्ट: true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**रिटर्न:**  
boolean  
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public final void setNoBreak(boolean value)
```

No break यह गुण वस्तु बॉक्स पर "unbreakable" गुण को निर्दिष्ट करता है। जब true हो, बॉक्स के भीतर कोई लाइन ब्रेक नहीं हो सकता। यह उन ऑपरेटर इम्यूलेटर्स के लिए महत्वपूर्ण हो सकता है जो एक से अधिक बाइनरी ऑपरेटर से बने होते हैं। जब यह तत्व निर्दिष्ट नहीं किया जाता, तो बॉक्स के अंदर ब्रेक हो सकते हैं। डिफ़ॉल्ट: true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**परिमाण:**  
| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public final boolean getDifferential()
```

Differential जब true हो, बॉक्स एक डिफरेंशियल के रूप में कार्य करता है (उदाहरण के लिए, \\ud835\\udc51\\ud835\\udc65 एक इंटेग्रैंड में), और गणितीय डिफरेंशियल के लिए उपयुक्त क्षैतिज स्पेसिंग प्राप्त करता है। डिफ़ॉल्ट: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**रिटर्न:**  
boolean  
### setDifferential(boolean value) {#setDifferential-boolean-}
```
public final void setDifferential(boolean value)
```

Differential जब true हो, बॉक्स एक डिफरेंशियल के रूप में कार्य करता है (उदाहरण के लिए, \\ud835\\udc51\\ud835\\udc65 एक इंटेग्रैंड में), और गणितीय डिफरेंशियल के लिए उपयुक्त क्षैतिज स्पेसिंग प्राप्त करता है। डिफ़ॉल्ट: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**परिमाण:**  
| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getAlignmentPoint() {#getAlignmentPoint--}
```
public final boolean getAlignmentPoint()
```

जब true हो, यह ऑपरेटर इम्यूलेटर एक संरेखण बिंदु के रूप में कार्य करता है; अर्थात्, अन्य समीकरणों में निर्धारित संरेखण बिंदुओं को इसके साथ संरेखित किया जा सकता है। डिफ़ॉल्ट: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**रिटर्न:**  
boolean  
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public final void setAlignmentPoint(boolean value)
```

जब true हो, यह ऑपरेटर इम्यूलेटर एक संरेखण बिंदु के रूप में कार्य करता है; अर्थात्, अन्य समीकरणों में निर्धारित संरेखण बिंदुओं को इसके साथ संरेखित किया जा सकता है। डिफ़ॉल्ट: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**परिमाण:**  
| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getExplicitBreak() {#getExplicitBreak--}
```
public final byte getExplicitBreak()
```

Explicit break यह निर्धारित करता है कि बॉक्स वस्तु की शुरुआत में लाइन ब्रेक है या नहीं, जिससे लाइन बॉक्स वस्तु की शुरुआत पर रैप हो। इसके अलावा यह पिछले गणितीय पंक्ति के ऑपरेटर की संख्या निर्दिष्ट करता है जिसे वर्तमान गणितीय पंक्ति के संरेखण बिंदु के रूप में उपयोग किया जाएगा; संभावित मान: 1..255 डिफ़ॉल्ट: 0 (कोई स्पष्ट ब्रेक नहीं)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**रिटर्न:**  
byte  
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public final void setExplicitBreak(byte value)
```

Explicit break यह निर्धारित करता है कि बॉक्स वस्तु की शुरुआत में लाइन ब्रेक है या नहीं, जिससे लाइन बॉक्स वस्तु की शुरुआत पर रैप हो। इसके अलावा यह पिछले गणितीय पंक्ति के ऑपरेटर की संख्या निर्दिष्ट करता है जिसे वर्तमान गणितीय पंक्ति के संरेखण बिंदु के रूप में उपयोग किया जाएगा; संभावित मान: 1..255 डिफ़ॉल्ट: 0 (कोई स्पष्ट ब्रेक नहीं)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**परिमाण:**  
| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

बच्चों के तत्व प्राप्त करें

**रिटर्न:**  
com.aspose.slides.IMathElement[]

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Control Character Properties

**रिटर्न:**  
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps