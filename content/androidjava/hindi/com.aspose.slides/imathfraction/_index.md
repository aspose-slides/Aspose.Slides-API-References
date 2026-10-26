---
title: IMathFraction
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: भिन्न रेखा द्वारा अलग किए गए अंशांक और हर से बनी भिन्न वस्तु को निर्दिष्ट करता है।
type: docs
url: /hi/com.aspose.slides/imathfraction/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFraction extends IMathElement
```

भिन्न वस्तु को परिभाषित करता है, जिसमें अंशांक और हर एक भिन्न रेखा द्वारा अलग होते हैं। भिन्न रेखा क्षैतिज या विकर्ण हो सकती है, यह भिन्न गुणों पर निर्भर करता है। भिन्न वस्तु को स्टैक फ़ंक्शन के रूप में भी प्रयोग किया जाता है, जो एक तत्व को दूसरे के ऊपर रखता है, बिना किसी भिन्न रेखा के।

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathFraction mathFraction2 = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```

## विधियां

| विधि | विवरण |
| --- | --- |
| [getFractionType()](#getFractionType--) | भिन्न प्रकार डिफ़ॉल्ट: Bar |
| [setFractionType(int value)](#setFractionType-int-) | भिन्न प्रकार डिफ़ॉल्ट: Bar |
| [getNumerator()](#getNumerator--) | अंश |
| [getDenominator()](#getDenominator--) | हर |
### getFractionType() {#getFractionType--}
```
public abstract int getFractionType()
```


भिन्न प्रकार डिफ़ॉल्ट: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```


**रिटर्न:**
int
### setFractionType(int value) {#setFractionType-int-}
```
public abstract void setFractionType(int value)
```


भिन्न प्रकार डिफ़ॉल्ट: Bar

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

**रिटर्न:**
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

**रिटर्न:**
[IMathElement](../../com.aspose.slides/imathelement)