---
title: MathSuperscriptElement
second_title: Aspose.Slides जावा API संदर्भ
description: एक superscript वस्तु को निर्दिष्ट करता है, जिसमें एक बेस और एक घटित आकार का superscript ऊपर और दायीं ओर स्थित होता है
type: docs
url: /hi/com.aspose.slides/mathsuperscriptelement/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)  
```
public final class MathSuperscriptElement extends BaseScript implements IMathSuperscriptElement
```

एक superscript वस्तु को निर्दिष्ट करता है, जो एक बेस और एक घटित आकार का superscript का सम्मिलन है, जो ऊपर और दायीं ओर स्थित होता है

--------------------

> ```
> Example:
>  
>  IMathSuperscriptElement superscriptElement = new MathematicalText("N").setSuperscript("i");
```
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [MathSuperscriptElement(IMathElement baseArg, IMathElement superScript)](#MathSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | MathSuperscriptElement वर्ग का नया उदाहरण आरंभ करता है। |
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getSuperscript()](#getSuperscript--) | Superscript |
| [getChildren()](#getChildren--) | बच्चों के तत्व प्राप्त करें |
### MathSuperscriptElement(IMathElement baseArg, IMathElement superScript) {#MathSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathSuperscriptElement(IMathElement baseArg, IMathElement superScript)
```


MathSuperscriptElement वर्ग का नया उदाहरण आरंभ करता है।

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  MathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| superScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```


Superscript

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  MathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
>  IMathElement super = superscriptElement.getSuperscript();
> ```


**वापसी:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


बच्चों के तत्व प्राप्त करें

**वापसी:**
com.aspose.slides.IMathElement[]