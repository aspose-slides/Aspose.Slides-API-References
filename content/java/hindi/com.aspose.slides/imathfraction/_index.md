---
title: IMathFraction
second_title: Aspose.Slides for Java API संदर्भ
description: भिन्न वस्तु को निर्दिष्ट करता है जो अंश और हर से मिलकर बनती है और एक भिन्न रेखा द्वारा विभक्त होती है।
type: docs
url: /hi/com.aspose.slides/imathfraction/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFraction extends IMathElement
```

भिन्न वस्तु को निर्दिष्ट करता है, जो अंश और हर से बनी होती है जो एक भिन्न रेखा द्वारा विभक्त होते हैं। भिन्न रेखा क्षैतिज या विकर्ण हो सकती है, यह भिन्न गुणों पर निर्भर करता है। भिन्न वस्तु का उपयोग स्टैक फ़ंक्शन को दर्शाने के लिए भी किया जाता है, जो एक तत्व को दूसरे के ऊपर रखता है, बिना किसी भिन्न रेखा के।

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathFraction mathFraction2 = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getFractionType()](#getFractionType--) | भिन्न प्रकार डिफ़ॉल्ट: बार |
| [setFractionType(int value)](#setFractionType-int-) | भिन्न प्रकार डिफ़ॉल्ट: बार |
| [getNumerator()](#getNumerator--) | अंश |
| [getDenominator()](#getDenominator--) | हर |
### getFractionType() {#getFractionType--}
```
public abstract int getFractionType()
```


भिन्न प्रकार डिफ़ॉल्ट: बार

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```


**वापसी:**
int
### setFractionType(int value) {#setFractionType-int-}
```
public abstract void setFractionType(int value)
```


भिन्न प्रकार डिफ़ॉल्ट: बार

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
public abstract IMathElement getNumerator()
```


अंश

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement numerator = mathFraction.getNumerator();
> ```

**वापसी:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDenominator() {#getDenominator--}
```
public abstract IMathElement getDenominator()
```


हर

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement denominator = mathFraction.getDenominator();
> ```


**वापसी:**
[IMathElement](../../com.aspose.slides/imathelement)