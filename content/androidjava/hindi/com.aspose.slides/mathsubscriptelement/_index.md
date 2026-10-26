---
title: MathSubscriptElement
second_title: Aspose.Slides Android के लिए Java API रेफ़रेंस के माध्यम से
description: नीचे और दाएँ स्थित एक बेस और घटे हुए आकार के सबस्क्रिप्ट से बने सबस्क्रिप्ट ऑब्जेक्ट को निर्दिष्ट करता है।
type: docs
url: /hi/com.aspose.slides/mathsubscriptelement/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
```
public final class MathSubscriptElement extends BaseScript implements IMathSubscriptElement
```

सबस्क्रिप्ट ऑब्जेक्ट को निर्दिष्ट करता है, जिसमें एक बेस और एक घटे हुए आकार का सबस्क्रिप्ट नीचे तथा दाएँ स्थित होता है।

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
>  ```

## Constructors

| निर्माता | विवरण |
| --- | --- |
| [MathSubscriptElement(IMathElement baseArg, IMathElement subScript)](#MathSubscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | MathSubscriptElement क्लास की नई इंस्टेंस को आरंभ करता है। |
## Methods

| विधि | विवरण |
| --- | --- |
| [getSubscript()](#getSubscript--) | सबस्क्रिप्ट |
| [getChildren()](#getChildren--) | संतान तत्व प्राप्त करें |
### MathSubscriptElement(IMathElement baseArg, IMathElement subScript) {#MathSubscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathSubscriptElement(IMathElement baseArg, IMathElement subScript)
```


MathSubscriptElement क्लास की नई इंस्टेंस को आरंभ करता है।

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| subScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```


सबस्क्रिप्ट

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement sub = subscriptElement.getSubscript();
> ```

**रिटर्न मान:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


संतान तत्व प्राप्त करें

**रिटर्न मान:**
com.aspose.slides.IMathElement[]