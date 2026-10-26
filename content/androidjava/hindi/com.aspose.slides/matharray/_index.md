---
title: MathArray
second_title: Aspose.Slides एंड्रॉइड के लिए जावा API रेफ़रेंस के माध्यम से
description: समीकरणों या किसी भी गणितीय वस्तुओं की एक लंबवत सरणी को निर्दिष्ट करता है
type: docs
url: /hi/com.aspose.slides/matharray/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IMathArray](../../com.aspose.slides/imatharray)  
```
public final class MathArray extends MathElementBase implements IMathArray
```

समीकरणों या किसी भी गणितीय वस्तुओं की एक लंबवत सरणी को निर्दिष्ट करता है

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [MathArray(IMathElement element)](#MathArray-com.aspose.slides.IMathElement-) | एक गणितीय सरणी बनाता है और निर्दिष्ट तत्व को उसमें रखता है |
| [MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)](#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | एक गणितीय सरणी बनाता है और निर्दिष्ट तत्वों को उसमें रखता है |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getArguments()](#getArguments--) | सरणी के आइटमों का सेट |
| [getBaseJustification()](#getBaseJustification--) | सरणी की संरेखण आसपास के पाठ के सापेक्ष निर्दिष्ट करता है। सरणी के बाहर का पाठ सरणी वस्तु के नीचे, ऊपर, या मध्य के साथ संरेखित किया जा सकता है। |
| [setBaseJustification(int value)](#setBaseJustification-int-) | सरणी की संरेखण आसपास के पाठ के सापेक्ष निर्दिष्ट करता है। सरणी के बाहर का पाठ सरणी वस्तु के नीचे, ऊपर, या मध्य के साथ संरेखित किया जा सकता है। |
| [getMaximumDistribution()](#getMaximumDistribution--) | अधिकतम वितरण। जब true हो, सरणी को अभ्यन्तर तत्व (पृष्ठ, स्तम्भ, कक्ष, आदि) की अधिकतम चौड़ाई तक फैलाया जाता है। |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | अधिकतम वितरण। जब true हो, सरणी को अभ्यन्तर तत्व (पृष्ठ, स्तम्भ, कक्ष, आदि) की अधिकतम चौड़ाई तक फैलाया जाता है। |
| [getObjectDistribution()](#getObjectDistribution--) | ऑब्जेक्ट वितरण। जब true हो, सरणी की सामग्री को सरणी वस्तु की अधिकतम चौड़ाई तक फैलाया जाता है। |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | ऑब्जेक्ट वितरण। जब true हो, सरणी की सामग्री को सरणी वस्तु की अधिकतम चौड़ाई तक फैलाया जाता है। |
| [getRowSpacingRule()](#getRowSpacingRule--) | सरणी तत्वों के बीच ऊर्ध्वाधर अंतराल का प्रकार। डिफॉल्ट: SingleLineGap |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | सरणी तत्वों के बीच ऊर्ध्वाधर अंतराल का प्रकार। डिफॉल्ट: SingleLineGap |
| [getRowSpacing()](#getRowSpacing--) | सरणी की पंक्तियों के बीच अंतराल। यह केवल तब उपयोग होता है जब RowSpacingRule को 3 पर सेट किया गया हो। ठीक उसी स्थिति में माप इकाई पॉइंट्स होती है या Multiple के लिए आधी-लाइनें। |
| [setRowSpacing(long value)](#setRowSpacing-long-) | सरणी की पंक्तियों के बीच अंतराल। यह केवल तब उपयोग होता है जब RowSpacingRule को 3 पर सेट किया गया हो। ठीक उसी स्थिति में माप इकाई पॉइंट्स होती है या Multiple के लिए आधी-लाइनें। |
| [getChildren()](#getChildren--) | संतान तत्व प्राप्त करें |
### MathArray(IMathElement element) {#MathArray-com.aspose.slides.IMathElement-}
```
public MathArray(IMathElement element)
```

एक गणितीय सरणी बनाता है और निर्दिष्ट तत्व को उसमें रखता है

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | सरणी में रखने के लिए तत्व |

### MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements) {#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)
```

एक गणितीय सरणी बनाता है और निर्दिष्ट तत्वों को उसमें रखता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| elements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | सरणी में रखने के लिए तत्व |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```

सरणी के आइटमों का सेट

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
> ```

**रिटर्न:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```

सरणी की संरेखण आसपास के पाठ के सापेक्ष निर्दिष्ट करता है। सरणी के बाहर का पाठ सरणी वस्तु के नीचे, ऊपर, या मध्य के साथ संरेखित किया जा सकता है। डिफॉल्ट मान: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**रिटर्न:**  
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```

सरणी की संरेखण आसपास के पाठ के सापेक्ष निर्दिष्ट करता है। सरणी के बाहर का पाठ सरणी वस्तु के नीचे, ऊपर, या मध्य के साथ संरेखित किया जा सकता है। डिफॉल्ट मान: Center

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

अधिकतम वितरण। जब true हो, सरणी को अभ्यन्तर तत्व (पृष्ठ, स्तम्भ, कक्ष, आदि) की अधिकतम चौड़ाई तक फैलाया जाता है।

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**रिटर्न:**
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public final void setMaximumDistribution(boolean value)
```

अधिकतम वितरण। जब true हो, सरणी को अभ्यन्तर तत्व (पृष्ठ, स्तम्भ, कक्ष, आदि) की अधिकतम चौड़ाई तक फैलाया जाता है।

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

ऑब्जेक्ट वितरण। जब true हो, सरणी की सामग्री को सरणी वस्तु की अधिकतम चौड़ाई तक फैलाया जाता है।

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**रिटर्न:**
boolean
### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public final void setObjectDistribution(boolean value)
```

ऑब्जेक्ट वितरण। जब true हो, सरणी की सामग्री को सरणी वस्तु की अधिकतम चौड़ाई तक फैलाया जाता है।

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

सरणी तत्वों के बीच ऊर्ध्वाधर अंतराल का प्रकार। डिफॉल्ट: SingleLineGap

--------------------

> ```
> उदाहरण:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**रिटर्न:**
int
### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public final void setRowSpacingRule(int value)
```

सरणी तत्वों के बीच ऊर्ध्वाधर अंतराल का प्रकार। डिफॉल्ट: SingleLineGap

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

सरणी की पंक्तियों के बीच अंतराल। यह केवल तब उपयोग होता है जब RowSpacingRule को 3 पर सेट किया गया हो। ठीक उसी स्थिति में माप इकाई पॉइंट्स होती है या Multiple के लिए आधी-लाइनें। डिफॉल्ट: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**रिटर्न:**
long
### setRowSpacing(long value) {#setRowSpacing-long-}
```
public final void setRowSpacing(long value)
```

सरणी की पंक्तियों के बीच अंतराल। यह केवल तब उपयोग होता है जब RowSpacingRule को 3 पर सेट किया गया हो। ठीक उसी स्थिति में माप इकाई पॉइंट्स होती है या Multiple के लिए आधी-लाइनें। डिफॉल्ट: 0

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

संतान तत्व प्राप्त करें

**रिटर्न:**
com.aspose.slides.IMathElement[]