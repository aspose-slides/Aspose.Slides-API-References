---
title: MathNaryOperator
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: Summation और Integral जैसे N-ary गणितीय वस्तु को निर्दिष्ट करता है।
type: docs
url: /hi/com.aspose.slides/mathnaryoperator/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IMathNaryOperator](../../com.aspose.slides/imathnaryoperator), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathNaryOperator extends MathElementBase implements IMathNaryOperator, IHasControlCharacterProperties
```

Specifies an N-ary गणितीय वस्तु, जैसे Summation और Integral। यह एक ऑपरेटर, एक बेस (या ऑपेंड), और वैकल्पिक ऊपरी तथा निचली सीमाओं से बना होता है। N-ary ऑपरेटर्स के उदाहरण हैं: Summation, Union, Intersection, Integral

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
```
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | MathNaryOperator क्लास की नई इंस्टेंस को प्रारंभ करता है। |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | MathNaryOperator क्लास की नई इंस्टेंस को प्रारंभ करता है। |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#MathNaryOperator-char-com.aspose.slides.IMathElement-) | MathNaryOperator क्लास की नई इंस्टेंस को प्रारंभ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getBase()](#getBase--) | बेस तर्क |
| [getSubscript()](#getSubscript--) | उदाहरण के लिए, इंटीग्रल के मामले में, निचली सीमा निर्धारित करने वाले सबस्क्रिप्ट तर्क को निर्दिष्ट करता है |
| [getSuperscript()](#getSuperscript--) | उदाहरण के लिए, इंटीग्रल के मामले में, ऊपरी सीमा निर्धारित करने वाले सुपरस्क्रिप्ट तर्क को निर्दिष्ट करता है |
| [getOperator()](#getOperator--) | Nary ऑपरेटर कैरेक्टर, उदाहरण के लिए: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | Nary ऑपरेटर कैरेक्टर, उदाहरण के लिए: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | सीमाओं का स्थान (सबस्क्रिप्ट और सुपरस्क्रिप्ट) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | सीमाओं का स्थान (सबस्क्रिप्ट और सुपरस्क्रिप्ट) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | ऑपरेटर कैरेक्टर अपने ऑपेंड की ऊँचाई से मेल खाने के लिए लंबवत बढ़ता है |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | ऑपरेटर कैरेक्टर अपने ऑपेंड की ऊँचाई से मेल खाने के लिए लंबवत बढ़ता है |
| [getHideSubscript()](#getHideSubscript--) | सबस्क्रिप्ट छुपाएँ |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | सबस्क्रिप्ट छुपाएँ |
| [getHideSuperscript()](#getHideSuperscript--) | सुपरस्क्रिप्ट छुपाएँ |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | सुपरस्क्रिप्ट छुपाएँ |
| [getChildren()](#getChildren--) | बच्चे तत्व प्राप्त करें |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | कंट्रोल कैरेक्टर गुण |
### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```

MathNaryOperator क्लास की नई इंस्टेंस को प्रारंभ करता है।

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i=0"), new MathematicalText("\ud835\udc5b"));
```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| operatorSymbol | char | Nary ऑपरेटर प्रतीक |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | बेस तर्क |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | निचली सीमा |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | ऊपरी सीमा |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```

MathNaryOperator क्लास की नई इंस्टेंस को प्रारंभ करता है।

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i"));
```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| operatorSymbol | char | Nary ऑपरेटर प्रतीक |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | बेस तर्क |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | निचली सीमा |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#MathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```

MathNaryOperator क्लास की नई इंस्टेंस को प्रारंभ करता है।

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"));
```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| operatorSymbol | char | Nary ऑपरेटर प्रतीक |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | बेस तर्क |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

बेस तर्क

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement baseArg = naryOperator.getBase();
> ```

**वापसी:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```

उदाहरण के लिए, इंटीग्रल के मामले में, निचली सीमा निर्धारित करने वाले सबस्क्रिप्ट तर्क को निर्दिष्ट करता है

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
> ```

**वापसी:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```

उदाहरण के लिए, इंटीग्रल के मामले में, ऊपरी सीमा निर्धारित करने वाले सुपरस्क्रिप्ट तर्क को निर्दिष्ट करता है

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**वापसी:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperator() {#getOperator--}
```
public final char getOperator()
```

Nary ऑपरेटर कैरेक्टर, उदाहरण के लिए: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**वापसी:**
char
### setOperator(char value) {#setOperator-char-}
```
public final void setOperator(char value)
```

Nary ऑपरेटर कैरेक्टर, उदाहरण के लिए: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | char |  |

### getLimitLocation() {#getLimitLocation--}
```
public final int getLimitLocation()
```

सीमाओं का स्थान (सबस्क्रिप्ट और सुपरस्क्रिप्ट)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**वापसी:**
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public final void setLimitLocation(int value)
```

सीमाओं का स्थान (सबस्क्रिप्ट और सुपरस्क्रिप्ट)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public final boolean getGrowToMatchOperandHeight()
```

ऑपरेटर कैरेक्टर अपने ऑपेंड की ऊँचाई से मेल खाने के लिए लंबवत बढ़ता है

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**वापसी:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```

ऑपरेटर कैरेक्टर अपने ऑपेंड की ऊँचाई से मेल खाने के लिए लंबवत बढ़ता है

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getHideSubscript() {#getHideSubscript--}
```
public final boolean getHideSubscript()
```

सबस्क्रिप्ट छुपाएँ

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**वापसी:**
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public final void setHideSubscript(boolean value)
```

सबस्क्रिप्ट छुपाएँ

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getHideSuperscript() {#getHideSuperscript--}
```
public final boolean getHideSuperscript()
```

सुपरस्क्रिप्ट छुपाएँ

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**वापसी:**
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public final void setHideSuperscript(boolean value)
```

सुपरस्क्रिप्ट छुपाएँ

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

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

कंट्रोल कैरेक्टर गुण

**वापसी:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps