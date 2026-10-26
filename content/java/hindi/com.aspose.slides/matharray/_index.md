---
title: MathArray
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: समीकरणों या किसी भी गणितीय वस्तुओं की लंबवत सरणी को निर्दिष्ट करता है
type: docs
url: /hi/com.aspose.slides/matharray/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**सभी लागू इंटरफेस:**
[com.aspose.slides.IMathArray](../../com.aspose.slides/imatharray)
```
public final class MathArray extends MathElementBase implements IMathArray
```

समीकरणों या किसी भी गणितीय वस्तुओं की लंबवत सरणी को निर्दिष्ट करता है

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## निर्माता

| निर्माताआ | विवरण |
| --- | --- |
| [MathArray(IMathElement element)](#MathArray-com.aspose.slides.IMathElement-) | एक गणितीय सरणी बनाता है और उसमें निर्दिष्ट तत्व रखता है |
| [MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)](#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | एक गणितीय सरणी बनाता है और उसमें निर्दिष्ट तत्व रखता है |
## विधियां

| विधि | विवरण |
| --- | --- |
| [getArguments()](#getArguments--) | ऐरे के आइटम का सेट |
| [getBaseJustification()](#getBaseJustification--) | ऐरे को आसपास के पाठ के सापेक्ष संरेखित करता है। ऐरे के बाहर का पाठ नीचे, ऊपर या केंद्र में संरेखित किया जा सकता है। |
| [setBaseJustification(int value)](#setBaseJustification-int-) | ऐरे को आसपास के पाठ के सापेक्ष संरेखित करता है। ऐरे के बाहर का पाठ नीचे, ऊपर या केंद्र में संरेखित किया जा सकता है। |
| [getMaximumDistribution()](#getMaximumDistribution--) | अधिकतम वितरण। जब true हो, तो ऐरे को सम्मिलित तत्व (पृष्ठ, स्तंभ, कोशिका आदि) की अधिकतम चौड़ाई तक फैलाया जाता है। |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | अधिकतम वितरण। जब true हो, तो ऐरे को सम्मिलित तत्व (पृष्ठ, स्तंभ, कोशिका आदि) की अधिकतम चौड़ाई तक फैलाया जाता है। |
| [getObjectDistribution()](#getObjectDistribution--) | ऑब्जेक्ट वितरण। जब true हो, तो ऐरे की सामग्री को ऐरे ऑब्जेक्ट की अधिकतम चौड़ाई तक फैलाया जाता है। |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | ऑब्जेक्ट वितरण। जब true हो, तो ऐरे की सामग्री को ऐरे ऑब्जेक्ट की अधिकतम चौड़ाई तक फैलाया जाता है। |
| [getRowSpacingRule()](#getRowSpacingRule--) | ऐरे तत्वों के बीच ऊर्ध्वाधर अंतराल का प्रकार। डिफ़ॉल्ट: SingleLineGap |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | ऐरे तत्वों के बीच ऊर्ध्वाधर अंतराल का प्रकार। डिफ़ॉल्ट: SingleLineGap |
| [getRowSpacing()](#getRowSpacing--) | ऐरे की पंक्तियों के बीच अंतराल। यह केवल तब उपयोग होता है जब RowSpacingRule को 3 पर सेट किया गया हो। ठीक स्थिति में माप इकाई पॉइंट्स है या कई में माप इकाई आधी-लाइनें। |
| [setRowSpacing(long value)](#setRowSpacing-long-) | ऐरे की पंक्तियों के बीच अंतराल। यह केवल तब उपयोग होता है जब RowSpacingRule को 3 पर सेट किया गया हो। ठीक स्थिति में माप इकाई पॉइंट्स है या कई में माप इकाई आधी-लाइनें। |
| [getChildren()](#getChildren--) | बच्चे तत्व प्राप्त करें |
### MathArray(IMathElement element) {#MathArray-com.aspose.slides.IMathElement-}
```
public MathArray(IMathElement element)
```

एक गणितीय सरणी बनाता है और उसमें निर्दिष्ट तत्व रखता है

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | ऐरे में रखे जाने वाला तत्व |

### MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements) {#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)
```

एक गणितीय सरणी बनाता है और उसमें निर्दिष्ट तत्व रखता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| elements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | ऐरे में रखे जाने वाले तत्व |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```

ऐरे के आइटम का सेट

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
> ```
**वापसी:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```

ऐरे को आसपास के पाठ के सापेक्ष संरेखित करता है। डिफ़ॉल्ट मान: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```
**वापसी:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```

ऐरे को आसपास के पाठ के सापेक्ष संरेखित करता है। डिफ़ॉल्ट मान: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```
**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getMaximumDistribution() {#getMaximumDistribution--}
```
public final boolean getMaximumDistribution()
```

अधिकतम वितरण। जब true हो, तो ऐरे को सम्मिलित तत्व (पृष्ठ, स्तंभ, कोशिका आदि) की अधिकतम चौड़ाई तक फैलाया जाता है।

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```
**वापसी:**
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public final void setMaximumDistribution(boolean value)
```

अधिकतम वितरण। जब true हो, तो ऐरे को सम्मिलित तत्व (पृष्ठ, स्तंभ, कोशिका आदि) की अधिकतम चौड़ाई तक फैलाया जाता है।

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```
**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getObjectDistribution() {#getObjectDistribution--}
```
public final boolean getObjectDistribution()
```

ऑब्जेक्ट वितरण। जब true हो, तो ऐरे की सामग्री को ऐरे ऑब्जेक्ट की अधिकतम चौड़ाई तक फैलाया जाता है।

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```
**वापसी:**
boolean
### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public final void setObjectDistribution(boolean value)
```

ऑब्जेक्ट वितरण। जब true हो, तो ऐरे की सामग्री को ऐरे ऑब्जेक्ट की अधिकतम चौड़ाई तक फैलाया जाता है।

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```
**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getRowSpacingRule() {#getRowSpacingRule--}
```
public final int getRowSpacingRule()
```

ऐरे तत्वों के बीच ऊर्ध्वाधर अंतराल का प्रकार। डिफ़ॉल्ट: SingleLineGap

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```
**वापसी:**
int
### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public final void setRowSpacingRule(int value)
```

ऐरे तत्वों के बीच ऊर्ध्वाधर अंतराल का प्रकार। डिफ़ॉल्ट: SingleLineGap

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```
**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getRowSpacing() {#getRowSpacing--}
```
public final long getRowSpacing()
```

ऐरे की पंक्तियों के बीच अंतराल। यह केवल तब उपयोग होता है जब RowSpacingRule को 3 पर सेट किया गया हो। ठीक स्थिति में माप इकाई पॉइंट्स है या कई में माप इकाई आधी-लाइनें। डिफ़ॉल्ट: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```
**वापसी:**
long
### setRowSpacing(long value) {#setRowSpacing-long-}
```
public final void setRowSpacing(long value)
```

ऐरे की पंक्तियों के बीच अंतराल। यह केवल तब उपयोग होता है जब RowSpacingRule को 3 पर सेट किया गया हो। ठीक स्थिति में माप इकाई पॉइंट्स है या कई में माप इकाई आधी-लाइनें। डिफ़ॉल्ट: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```
**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

बच्चे तत्व प्राप्त करें

**वापसी:**
com.aspose.slides.IMathElement[]