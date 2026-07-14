---
title: IMathBox
second_title: Android के लिए Aspose.Slides, Java API संदर्भ के द्वारा
description: गणितीय तत्व की तर्कसंगत बॉक्सिंग पैकेजिंग को निर्दिष्ट करता है।
type: docs
url: /hi/com.aspose.slides/imathbox/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBox extends IMathElement
```

गणितीय तत्व के तर्कसंगत बॉक्सिंग (पैकेजिंग) को निर्दिष्ट करता है। उदाहरण के लिए, एक बॉक्स्ड ऑब्जेक्ट एक ऑपरेटर इम्यूलेटर के रूप में उपयोग किया जा सकता है, चाहे उसमें संरेखण बिंदु हो या न हो, इसे लाइन ब्रेक बिंदु के रूप में उपयोग किया जा सकता है, या इस प्रकार समूहित किया जा सकता है कि बॉक्स के भीतर लाइन ब्रेक न हो सके। उदाहरण के लिए, “==” ऑपरेटर को लाइन ब्रेक को रोकने के लिए बॉक्स किया जाना चाहिए।

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
> ```
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getBase()](#getBase--) | आधार तर्क |
| [getOperatorEmulator()](#getOperatorEmulator--) | ऑपरेटर इम्यूलेटर। |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | ऑपरेटर इम्यूलेटर। |
| [getNoBreak()](#getNoBreak--) | कोई ब्रेक नहीं। |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | कोई ब्रेक नहीं। |
| [getDifferential()](#getDifferential--) | डिफरेंशियल। |
| [setDifferential(boolean value)](#setDifferential-boolean-) | डिफरेंशियल। |
| [getAlignmentPoint()](#getAlignmentPoint--) | जब सत्य हो, यह ऑपरेटर इम्यूलेटर एक संरेखण बिंदु के रूप में कार्य करता है; अर्थात, अन्य समीकरणों में निर्दिष्ट संरेखण बिंदुओं को इसके साथ संरेखित किया जा सकता है। |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | जब सत्य हो, यह ऑपरेटर इम्यूलेटर एक संरेखण बिंदु के रूप में कार्य करता है; अर्थात, अन्य समीकरणों में निर्दिष्ट संरेखण बिंदुओं को इसके साथ संरेखित किया जा सकता है। |
| [getExplicitBreak()](#getExplicitBreak--) | स्पष्ट ब्रेक यह निर्धारित करता है कि क्या बॉक्स ऑब्जेक्ट की शुरुआत में लाइन ब्रेक है, जिससे लाइन बॉक्स ऑब्जेक्ट की शुरुआत पर रैप हो। |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | स्पष्ट ब्रेक यह निर्धारित करता है कि क्या बॉक्स ऑब्जेक्ट की शुरुआत में लाइन ब्रेक है, जिससे लाइन बॉक्स ऑब्जेक्ट की शुरुआत पर रैप हो। |

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
> ```

**रिटर्न:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public abstract boolean getOperatorEmulator()
```

ऑपरेटर इम्यूलेटर। जब सत्य हो, बॉक्स और उसके सामग्री एकल ऑपरेटर के रूप में व्यवहार करती हैं और ऑपरेटर की विशेषताओं को विरासत में लेती हैं। इसका अर्थ है, उदाहरण के लिए, यह अक्षर लाइन ब्रेक के बिंदु के रूप में उपयोग किया जा सकता है और अन्य ऑपरेटरों के साथ संरेखित किया जा सकता है। ऑपरेटर इम्यूलेटर अक्सर तब उपयोग किए जाते हैं जब एक या अधिक ग्लीफ़ मिलकर एक ऑपरेटर बनाते हैं, जैसे '=='. डिफ़ॉल्ट मान: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**रिटर्न:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public abstract void setOperatorEmulator(boolean value)
```

ऑपरेटर इम्यूलेटर। जब सत्य हो, बॉक्स और उसके सामग्री एकल ऑपरेटर के रूप में व्यवहार करती हैं और ऑपरेटर की विशेषताओं को विरासत में लेती हैं। इसका अर्थ है, उदाहरण के लिए, यह अक्षर लाइन ब्रेक के बिंदु के रूप में उपयोग किया जा सकता है और अन्य ऑपरेटरों के साथ संरेखित किया जा सकता है। ऑपरेटर इम्यूलेटर अक्सर तब उपयोग किए जाते हैं जब एक या अधिक ग्लीफ़ मिलकर एक ऑपरेटर बनाते हैं, जैसे '=='. डिफ़ॉल्ट मान: false

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

कोई ब्रेक नहीं। यह प्रॉपर्टी ऑब्जेक्ट बॉक्स पर "unbreakable" प्रॉपर्टी को निर्दिष्ट करती है। जब सत्य हो, बॉक्स के भीतर कोई लाइन ब्रेक नहीं हो सकता। यह उन ऑपरेटर इम्यूलेटरों के लिए महत्वपूर्ण हो सकता है जो एक से अधिक बाइनरी ऑपरेटर से बनते हैं। जब यह तत्व निर्दिष्ट नहीं किया जाता, तो बॉक्स के अंदर ब्रेक हो सकता है। डिफ़ॉल्ट: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**रिटर्न:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public abstract void setNoBreak(boolean value)
```

कोई ब्रेक नहीं। यह प्रॉपर्टी ऑब्जेक्ट बॉक्स पर "unbreakable" प्रॉपर्टी को निर्दिष्ट करती है। जब सत्य हो, बॉक्स के भीतर कोई लाइन ब्रेक नहीं हो सकता। यह उन ऑपरेटर इम्यूलेटरों के लिए महत्वपूर्ण हो सकता है जो एक से अधिक बाइनरी ऑपरेटर से बनते हैं। जब यह तत्व निर्दिष्ट नहीं किया जाता, तो बॉक्स के अंदर ब्रेक हो सकता है। डिफ़ॉल्ट: true

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

डिफरेंशियल। जब सत्य हो, बॉक्स एक डिफरेंशियल के रूप में कार्य करता है (उदाहरण के लिए, \\ud835\\udc51\\ud835\\udc65 एक इंटीग्रैंड में), और गणितीय डिफरेंशियल के लिए उपयुक्त क्षैतिज अंतराल प्राप्त करता है। डिफ़ॉल्ट: false

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
public abstract void setDifferential(boolean value)
```

डिफरेंशियल। जब सत्य हो, बॉक्स एक डिफरेंशियल के रूप में कार्य करता है (उदाहरण के लिए, \\ud835\\udc51\\ud835\\udc65 एक इंटीग्रैंड में), और गणितीय डिफरेंशियल के लिए उपयुक्त क्षैतिज अंतराल प्राप्त करता है। डिफ़ॉल्ट: false

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

जब सत्य हो, यह ऑपरेटर इम्यूलेटर एक संरेखण बिंदु के रूप में कार्य करता है; अर्थात, अन्य समीकरणों में निर्दिष्ट संरेखण बिंदुओं को इसके साथ संरेखित किया जा सकता है। डिफ़ॉल्ट: false

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
public abstract void setAlignmentPoint(boolean value)
```

जब सत्य हो, यह ऑपरेटर इम्यूलेटर एक संरेखण बिंदु के रूप में कार्य करता है; अर्थात, अन्य समीकरणों में निर्दिष्ट संरेखण बिंदुओं को इसके साथ संरेखित किया जा सकता है। डिफ़ॉल्ट: false

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

स्पष्ट ब्रेक यह निर्धारित करता है कि क्या बॉक्स ऑब्जेक्ट की शुरुआत में लाइन ब्रेक है, जिससे लाइन बॉक्स ऑब्जेक्ट की शुरुआत पर रैप हो। यह गणितीय टेक्स्ट की पिछली लाइन में ऑपरेटर की संख्या को निर्दिष्ट करता है जिसे वर्तमान लाइन के लिए संरेखण बिंदु के रूप में उपयोग किया जाएगा। संभावित मान: 1..255 डिफ़ॉल्ट: 0 (कोई स्पष्ट ब्रेक नहीं)

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
public abstract void setExplicitBreak(byte value)
```

स्पष्ट ब्रेक यह निर्धारित करता है कि क्या बॉक्स ऑब्जेक्ट की शुरुआत में लाइन ब्रेक है, जिससे लाइन बॉक्स ऑब्जेक्ट की शुरुआत पर रैप हो। यह गणितीय टेक्स्ट की पिछली लाइन में ऑपरेटर की संख्या को निर्दिष्ट करता है जिसे वर्तमान लाइन के लिए संरेखण बिंदु के रूप में उपयोग किया जाएगा। संभावित मान: 1..255 डिफ़ॉल्ट: 0 (कोई स्पष्ट ब्रेक नहीं)

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