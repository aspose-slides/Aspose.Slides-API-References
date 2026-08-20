---
title: MathSubscriptElement
second_title: Aspose.Slides for Java API संदर्भ
description: नीचे और दाईं ओर रखे गए बेस और छोटे आकार के सबस्क्रिप्ट से बना सबस्क्रिप्ट ऑब्जेक्ट निर्धारित करता है।
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

सबस्क्रिप्ट ऑब्जेक्ट को निर्दिष्ट करता है, जिसमें एक बेस और नीचे तथा दाईं ओर स्थित एक छोटा-साइज़ वाला सबस्क्रिप्ट होता है।

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
> ```
## कन्स्ट्रक्टर

| Constructor | Description |
| --- | --- |
| [MathSubscriptElement(IMathElement baseArg, IMathElement subScript)](#MathSubscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | MathSubscriptElement क्लास का नया उदाहरण प्रारंभ करता है। |
## मेथड्स

| Method | Description |
| --- | --- |
| [getSubscript()](#getSubscript--) | सबस्क्रिप्ट |
| [getChildren()](#getChildren--) | चाइल्ड तत्व प्राप्त करें |
### MathSubscriptElement(IMathElement baseArg, IMathElement subScript) {#MathSubscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathSubscriptElement(IMathElement baseArg, IMathElement subScript)
```

MathSubscriptElement क्लास का नया उदाहरण प्रारंभ करता है।

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
> ```

**पैरामीटर:**
| Parameter | Type | Description |
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

**रिटर्न:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

चाइल्ड तत्व प्राप्त करें

**रिटर्न:**
com.aspose.slides.IMathElement[]