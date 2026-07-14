---
title: IMathArray
second_title: Aspose.Slides Android के लिए Java API संदर्भ के माध्यम से
description: समीकरणों या किसी भी गणितीय वस्तु की एक ऊर्ध्वाधर सरणी निर्दिष्ट करता है
type: docs
url: /hi/com.aspose.slides/imatharray/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathArray extends IMathElement
```

समीकरणों या किसी भी गणितीय वस्तु का एक ऊर्ध्वाधर सरणी निर्दिष्ट करता है

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getArguments()](#getArguments--) | ऐरे के आइटमों का सेट |
| [getBaseJustification()](#getBaseJustification--) | ऐरे को आसपास के पाठ के सापेक्ष संरेखित करना निर्दिष्ट करता है। ऐरे के बाहर का पाठ ऐरे वस्तु के नीचे, ऊपर या मध्य में संरेखित किया जा सकता है। |
| [setBaseJustification(int value)](#setBaseJustification-int-) | ऐरे को आसपास के पाठ के सापेक्ष संरेखित करना निर्दिष्ट करता है। ऐरे के बाहर का पाठ ऐरे वस्तु के नीचे, ऊपर या मध्य में संरेखित किया जा सकता है। |
| [getMaximumDistribution()](#getMaximumDistribution--) | Maximum Distribution जब true हो, तो ऐरे को समाहित तत्व (पृष्ठ, कॉलम, सेल, आदि) की अधिकतम चौड़ाई तक फैलाया जाता है। |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Maximum Distribution जब true हो, तो ऐरे को समाहित तत्व (पृष्ठ, कॉलम, सेल, आदि) की अधिकतम चौड़ाई तक फैलाया जाता है। |
| [getObjectDistribution()](#getObjectDistribution--) | Object Distribution जब true हो, तो ऐरे की सामग्री को ऐरे वस्तु की अधिकत्तम चौड़ाई तक फैलाया जाता है। |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Object Distribution जब true हो, तो ऐरे की सामग्री को ऐरे वस्तु की अधिकत्तम चौड़ाई तक फैलाया जाता है। |
| [getRowSpacingRule()](#getRowSpacingRule--) | ऐरे तत्वों के बीच ऊर्ध्वाधर अंतराल का प्रकार |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | ऐरे तत्वों के बीच ऊर्ध्वाधर अंतराल का प्रकार |
| [getRowSpacing()](#getRowSpacing--) | ऐरे की पंक्तियों के बीच अंतराल। यह केवल तब उपयोग किया जाता है जब RowSpacingRule को 3 पर सेट किया गया हो। इस स्थिति में माप की इकाई पॉइंट्स है, या Multiple होने पर आधी लाइनों की इकाई। |
| [setRowSpacing(long value)](#setRowSpacing-long-) | ऐरे की पंक्तियों के बीच अंतराल। यह केवल तब उपयोग किया जाता है जब RowSpacingRule को 3 पर सेट किया गया हो। इस स्थिति में माप की इकाई पॉइंट्स है, या Multiple होने पर आधी लाइनों की इकाई। |

### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

ऐरे के आइटमों का सेट

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
public abstract int getBaseJustification()
```

ऐरे को आसपास के पाठ के सापेक्ष संरेखित करना निर्दिष्ट करता है। ऐरे के बाहर का पाठ ऐरे वस्तु के नीचे, ऊपर या मध्य में संरेखित किया जा सकता है। डिफ़ॉल्ट मान: Center

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
public abstract void setBaseJustification(int value)
```

ऐरे को आसपास के पाठ के सापेक्ष संरेखित करना निर्दिष्ट करता है। ऐरे के बाहर का पाठ ऐरे वस्तु के नीचे, ऊपर या मध्य में संरेखित किया जा सकता है। डिफ़ॉल्ट मान: Center

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
public abstract boolean getMaximumDistribution()
```

Maximum Distribution जब true हो, तो ऐरे को समाहित तत्व (पृष्ठ, कॉलम, सेल, आदि) की अधिकतम चौड़ाई तक फैलाया जाता है।

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
public abstract void setMaximumDistribution(boolean value)
```

Maximum Distribution जब true हो, तो ऐरे को समाहित तत्व (पृष्ठ, कॉलम, सेल, आदि) की अधिकतम चौड़ाई तक फैलाया जाता है।

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
public abstract boolean getObjectDistribution()
```

Object Distribution जब true हो, तो ऐरे की सामग्री को ऐरे वस्तु की अधिकत्तम चौड़ाई तक फैलाया जाता है।

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
public abstract void setObjectDistribution(boolean value)
```

Object Distribution जब true हो, तो ऐरे की सामग्री को ऐरे वस्तु की अधिकत्तम चौड़ाई तक फैलाया जाता है।

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
public abstract int getRowSpacingRule()
```

ऐरे तत्वों के बीच ऊर्ध्वाधर अंतराल का प्रकार

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
public abstract void setRowSpacingRule(int value)
```

ऐरे तत्वों के बीच ऊर्ध्वाधर अंतराल का प्रकार

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
public abstract long getRowSpacing()
```

ऐरे की पंक्तियों के बीच अंतराल। यह केवल तब उपयोग किया जाता है जब RowSpacingRule को 3 पर सेट किया गया हो। इस स्थिति में माप की इकाई पॉइंट्स है, या Multiple होने पर आधी लाइनों की इकाई। डिफ़ॉल्ट: 0

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
public abstract void setRowSpacing(long value)
```

ऐरे की पंक्तियों के बीच अंतराल। यह केवल तब उपयोग किया जाता है जब RowSpacingRule को 3 पर सेट किया गया हो। इस स्थिति में माप की इकाई पॉइंट्स है, या Multiple होने पर आधी लाइनों की इकाई। डिफ़ॉल्ट: 0

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