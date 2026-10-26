---
title: MathBox
second_title: Aspose.Slides for Android के माध्यम से Java API संदर्भ
description: गणितीय तत्व की तार्किक बोक्सिंग पैकेजिंग निर्दिष्ट करता है।
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

गणितीय तत्व का तार्किक बोक्सिंग (पैकेजिंग) निर्दिष्ट करता है। उदाहरण के लिए, एक बोक्स्ड ऑब्जेक्ट एक ऑपरेटर एम्यूलेटर के रूप में कार्य कर सकता है, संरेखण बिंदु के साथ या बिना, एक लाइन ब्रेक बिंदु के रूप में कार्य कर सकता है, या इस तरह समूहित हो सकता है कि उसके भीतर लाइन ब्रेक की अनुमति न हो। उदाहरण के रूप में, "==" ऑपरेटर को लाइन ब्रेक को रोकने के लिए बोक्स्ड होना चाहिए।

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [MathBox(IMathElement element)](#MathBox-com.aspose.slides.IMathElement-) | निर्दिष्ट तत्व को तर्क के रूप में प्रयोग कर MathBox को आरंभ करता है। |

## Methods

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | बेस तर्क |
| [getOperatorEmulator()](#getOperatorEmulator--) | Operator Emulator. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Operator Emulator. |
| [getNoBreak()](#getNoBreak--) | No break यह प्रॉपर्टी ऑब्जेक्ट बॉक्स पर "unbreakable" प्रॉपर्टी को निर्दिष्ट करती है। |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | No break यह प्रॉपर्टी ऑब्जेक्ट बॉक्स पर "unbreakable" प्रॉपर्टी को निर्दिष्ट करती है। |
| [getDifferential()](#getDifferential--) | Differential जब true हो, बॉक्स एक differential के रूप में कार्य करता है (उदाहरण के लिए, \\ud835\\udc51\\ud835\\udc65 एक इंटेग्रैंड में), और गणितीय differential के लिए उपयुक्त क्षैतिज स्पेसिंग प्राप्त करता है। |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Differential जब true हो, बॉक्स एक differential के रूप में कार्य करता है (उदाहरण के लिए, \\ud835\\udc51\\ud835\\udc65 एक इंटेग्रैंड में), और गणितीय differential के लिए उपयुक्त क्षैतिज स्पेसिंग प्राप्त करता है। |
| [getAlignmentPoint()](#getAlignmentPoint--) | जब true हो, यह operator emulator एक alignment point के रूप में कार्य करता है; अर्थात, अन्य समीकरणों में निर्धारित alignment points को इसके साथ संरेखित किया जा सकता है। |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | जब true हो, यह operator emulator एक alignment point के रूप में कार्य करता है; अर्थात, अन्य समीकरणों में निर्धारित alignment points को इसके साथ संरेखित किया जा सकता है। |
| [getExplicitBreak()](#getExplicitBreak--) | Explicit break निर्धारित करता है कि बॉक्स ऑब्जेक्ट की शुरुआत में लाइन ब्रेक है या नहीं, जिससे लाइन बॉक्स ऑब्जेक्ट की शुरुआत पर रैप हो। |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Explicit break निर्धारित करता है कि बॉक्स ऑब्जेक्ट की शुरुआत में लाइन ब्रेक है या नहीं, जिससे लाइन बॉक्स ऑब्जेक्ट की शुरुआत पर रैप हो। |
| [getChildren()](#getChildren--) | चाइल्ड एलिमेंट्स प्राप्त करें |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |

### MathBox(IMathElement element) {#MathBox-com.aspose.slides.IMathElement-}
```
public MathBox(IMathElement element)
```

निर्दिष्ट तत्व को तर्क के रूप में प्रयोग कर MathBox को आरंभ करता है।

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | बॉक्स जिस बेस तत्व पर लागू किया जाता है। यह null हो सकता है। |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

बेस तर्क

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

Operator Emulator. जब true हो, बॉक्स और उसकी सामग्री एक ही ऑपरेटर के रूप में व्यवहार करती है और ऑपरेटर की प्रॉपर्टी को विरासत में लेती है। इसका अर्थ है, उदाहरण के लिए, कि अक्षर एक लाइन ब्रेक बिंदु के रूप में कार्य कर सकता है और अन्य ऑपरेटरों के साथ संरेखित किया जा सकता है। ऑपरेटर एम्यूलेटर अक्सर तब उपयोग होते हैं जब एक या अधिक glyphs मिलकर एक ऑपरेटर बनाते हैं, जैसे '=='. डिफ़ॉल्ट मान: false

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**रिटर्न:** boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public final void setOperatorEmulator(boolean value)
```

Operator Emulator. जब true हो, बॉक्स और उसकी सामग्री एक ही ऑपरेटर के रूप में व्यवहार करती है और ऑपरेटर की प्रॉपर्टी को विरासत में लेती है। इसका अर्थ है, उदाहरण के लिए, कि अक्षर एक लाइन ब्रेक बिंदु के रूप में कार्य कर सकता है और अन्य ऑपरेटरों के साथ संरेखित किया जा सकता है। ऑपरेटर एम्यूलेटर अक्सर तब उपयोग होते हैं जब एक या अधिक glyphs मिलकर एक ऑपरेटर बनाते हैं, जैसे '=='. डिफ़ॉल्ट मान: false

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public final boolean getNoBreak()
```

No break यह प्रॉपर्टी ऑब्जेक्ट बॉक्स पर "unbreakable" प्रॉपर्टी को निर्दिष्ट करती है। जब true हो, बॉक्स के भीतर कोई लाइन ब्रेक नहीं हो सकता। यह कई बाइनरी ऑपरेटरों से बने ऑपरेटर एम्यूलेटर के लिए महत्वपूर्ण हो सकता है। जब यह तत्व निर्दिष्ट नहीं किया जाता, तो बॉक्स के अंदर ब्रेक हो सकते हैं। डिफ़ॉल्ट: true

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**रिटर्न:** boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public final void setNoBreak(boolean value)
```

No break यह प्रॉपर्टी ऑब्जेक्ट बॉक्स पर "unbreakable" प्रॉपर्टी को निर्दिष्ट करती है। जब true हो, बॉक्स के भीतर कोई लाइन ब्रेक नहीं हो सकता। यह कई बाइनरी ऑपरेटरों से बने ऑपरेटर एम्यूलेटर के लिए महत्वपूर्ण हो सकता है। जब यह तत्व निर्दिष्ट नहीं किया जाता, तो बॉक्स के अंदर ब्रेक हो सकते हैं। डिफ़ॉल्ट: true

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public final boolean getDifferential()
```

Differential जब true हो, बॉक्स एक differential के रूप में कार्य करता है (उदाहरण के लिए, \\ud835\\udc51\\ud835\\udc65 एक इंटेग्रैंड में), और गणितीय differential के लिए उपयुक्त क्षैतिज स्पेसिंग प्राप्त करता है। डिफ़ॉल्ट: false

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**रिटर्न:** boolean
### setDifferential(boolean value) {#setDifferential-boolean-}
```
public final void setDifferential(boolean value)
```

Differential जब true हो, बॉक्स एक differential के रूप में कार्य करता है (उदाहरण के लिए, \\ud835\\udc51\\ud835\\udc65 एक इंटेग्रैंड में), और गणितीय differential के लिए उपयुक्त क्षैतिज स्पेसिंग प्राप्त करता है। डिफ़ॉल्ट: false

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
public final boolean getAlignmentPoint()
```

जब true हो, यह operator emulator एक alignment point के रूप में कार्य करता है; अर्थात, अन्य समीकरणों में निर्धारित alignment points को इसके साथ संरेखित किया जा सकता है। डिफ़ॉल्ट: false

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**रिटर्न:** boolean
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public final void setAlignmentPoint(boolean value)
```

जब true हो, यह operator emulator एक alignment point के रूप में कार्य करता है; अर्थात, अन्य समीकरणों में निर्धारित alignment points को इसके साथ संरेखित किया जा सकता है। डिफ़ॉल्ट: false

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
public final byte getExplicitBreak()
```

Explicit break निर्धारित करता है कि बॉक्स ऑब्जेक्ट की शुरुआत में लाइन ब्रेक है या नहीं, जिससे लाइन बॉक्स ऑब्जेक्ट की शुरुआत पर रैप हो। यह गणितीय टेक्स्ट की पिछली लाइन में ऑपरेटर की संख्या निर्दिष्ट करता है जो वर्तमान लाइन के गणितीय टेक्स्ट के लिए alignment point के रूप में उपयोग होगी। संभावित मान: 1..255 डिफ़ॉल्ट: 0 (कोई explicit break नहीं)

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**रिटर्न:** byte
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public final void setExplicitBreak(byte value)
```

Explicit break निर्धारित करता है कि बॉक्स ऑब्जेक्ट की शुरुआत में लाइन ब्रेक है या नहीं, जिससे लाइन बॉक्स ऑब्जेक्ट की शुरुआत पर रैप हो। यह गणितीय टेक्स्ट की पिछली लाइन में ऑपरेटर की संख्या निर्दिष्ट करता है जो वर्तमान लाइन के गणितीय टेक्स्ट के लिए alignment point के रूप में उपयोग होगी। संभावित मान: 1..255 डिफ़ॉल्ट: 0 (कोई explicit break नहीं)

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

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

चाइल्ड एलिमेंट्स प्राप्त करें

**रिटर्न:** com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Control Character Properties

**रिटर्न:** com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps