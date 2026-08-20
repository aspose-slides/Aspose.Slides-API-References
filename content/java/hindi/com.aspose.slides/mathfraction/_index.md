---
title: MathFraction
second_title: Aspose.Slides के लिए Java API संदर्भ
description: एक numerator और denominator से बना fraction object निर्दिष्ट करता है, जो एक fraction bar द्वारा अलग किया जाता है।
type: docs
url: /hi/com.aspose.slides/mathfraction/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**सभी लागू इंटरफेस:**
[com.aspose.slides.IMathFraction](../../com.aspose.slides/imathfraction), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathFraction extends MathElementBase implements IMathFraction, IHasControlCharacterProperties
```

एक fraction object को निर्दिष्ट करता है, जो एक numerator और denominator से बना होता है जो एक fraction bar द्वारा अलग किए जाते हैं। fraction bar को आड़े या तिरछे रूप में रखा जा सकता है, यह fraction properties पर निर्भर करता है। fraction object का उपयोग stack function को दर्शाने के लिए भी किया जाता है, जो एक तत्व को दूसरे के ऊपर रखता है, बिना fraction bar के।

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
```
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | निर्दिष्ट numerator, denominator और type के साथ MathFraction को आरंभ करता है |
| [MathFraction(IMathElement numerator, IMathElement denominator)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | निर्दिष्ट numerator और denominator के साथ type 'Bar' का MathFraction आरंभ करता है |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getFractionType()](#getFractionType--) | Fraction type Default: Bar |
| [setFractionType(int value)](#setFractionType-int-) | Fraction type Default: Bar |
| [getNumerator()](#getNumerator--) | Numerator |
| [getDenominator()](#getDenominator--) | Denominator |
| [getChildren()](#getChildren--) | बच्चों के तत्व प्राप्त करें |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
### MathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```

निर्दिष्ट numerator, denominator और type के साथ MathFraction को आरंभ करता है

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Numerator |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Denominator |
| fractionType | int | Fraction type |

### MathFraction(IMathElement numerator, IMathElement denominator) {#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathFraction(IMathElement numerator, IMathElement denominator)
```

type 'Bar' का MathFraction निर्दिष्ट numerator और denominator के साथ आरंभ करता है

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"));
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Numerator |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Denominator |

### getFractionType() {#getFractionType--}
```
public final int getFractionType()
```

Fraction type Default: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**वापसी मान:**
int
### setFractionType(int value) {#setFractionType-int-}
```
public final void setFractionType(int value)
```

Fraction type Default: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getNumerator() {#getNumerator--}
```
public final IMathElement getNumerator()
```

Numerator

--------------------

> ```
> उदाहरण:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement numerator = mathFraction.getNumerator();
> ```

**वापसी मान:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDenominator() {#getDenominator--}
```
public final IMathElement getDenominator()
```

Denominator

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement denominator = mathFraction.getDenominator();
> ```

**वापसी मान:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

बच्चों के तत्व प्राप्त करें

**वापसी मान:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Control Character Properties

**वापसी मान:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps