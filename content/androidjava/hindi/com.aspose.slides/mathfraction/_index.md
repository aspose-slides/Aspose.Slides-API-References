---
title: MathFraction
second_title: Aspose.Slides for Android के लिए Java API रेफरेंस
description: फ़्रैक्शन बार द्वारा अलग किए गए अंश और हर से बनी फ़्रैक्शन ऑब्जेक्ट को निर्दिष्ट करता है।
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

यह फ़्रैक्शन ऑब्जेक्ट को निर्दिष्ट करता है, जिसमें अंश और हर फ़्रैक्शन बार द्वारा अलग होते हैं। फ़्रैक्शन बार क्षैतिज या तिर्यक हो सकता है, यह फ़्रैक्शन प्रॉपर्टीज़ पर निर्भर करता है। फ़्रैक्शन ऑब्जेक्ट का उपयोग स्टैक फ़ंक्शन को दर्शाने के लिए भी किया जाता है, जो एक तत्व को दूसरे के ऊपर रखता है, बिना फ़्रैक्शन बार के।

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | निर्दिष्ट न्यूमेरटर, डिनॉमिनेटर और प्रकार के साथ MathFraction को प्रारंभ करता है |
| [MathFraction(IMathElement numerator, IMathElement denominator)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | निर्दिष्ट न्यूमेरटर और डिनॉमिनेटर के साथ प्रकार 'Bar' का MathFraction प्रारंभ करता है |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getFractionType()](#getFractionType--) | फ़्रैक्शन प्रकार डिफ़ॉल्ट: Bar |
| [setFractionType(int value)](#setFractionType-int-) | फ़्रैक्शन प्रकार डिफ़ॉल्ट: Bar |
| [getNumerator()](#getNumerator--) | Numerator |
| [getDenominator()](#getDenominator--) | Denominator |
| [getChildren()](#getChildren--) | बच्चे तत्व प्राप्त करें |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
### MathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```

निर्दिष्ट न्यूमेरटर, डिनॉमिनेटर और प्रकार के साथ MathFraction को प्रारंभ करता है

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
| fractionType | int | फ़्रैक्शन प्रकार |

### MathFraction(IMathElement numerator, IMathElement denominator) {#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathFraction(IMathElement numerator, IMathElement denominator)
```

निर्दिष्ट न्यूमेरटर और डिनॉमिनेटर के साथ प्रकार 'Bar' का MathFraction प्रारंभ करता है

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

फ़्रैक्शन प्रकार डिफ़ॉल्ट: Bar

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
public final void setFractionType(int value)
```

फ़्रैक्शन प्रकार डिफ़ॉल्ट: Bar

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
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement numerator = mathFraction.getNumerator();
> ```

**वापसी:**
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

**वापसी:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

बच्चे तत्व प्राप्त करें

**वापसी:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Control Character Properties

**वापसी:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps