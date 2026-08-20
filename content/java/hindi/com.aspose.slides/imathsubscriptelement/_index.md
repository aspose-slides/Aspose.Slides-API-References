---
title: IMathSubscriptElement
second_title: Aspose.Slides जावा के लिए API संदर्भ
description: विशिष्ट करता है वह सबस्क्रिप्ट ऑब्जेक्ट जो एक बेस और एक छोटा आकार का सबस्क्रिप्ट शामिल करता है, जो नीचे और दाएँ रखा जाता है।
type: docs
url: /hi/com.aspose.slides/imathsubscriptelement/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSubscriptElement extends IMathElement
```

Specifies the subscript object, which consists of a base and a reduced-size subscript placed below and to the right.

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
> ```
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getBase()](#getBase--) | बेस तर्क |
| [getSubscript()](#getSubscript--) | सबस्क्रिप्ट |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

बेस तर्क

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement baseElem = subscriptElement.getBase();
> ```

**रिटर्न:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
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