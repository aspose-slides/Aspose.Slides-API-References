---
title: MathNaryOperator
second_title: Aspose.Slides के लिए Java API संदर्भ
description: Summation और Integral जैसे N-ary गणितीय वस्तु को निर्दिष्ट करता है।
type: docs
url: /hi/com.aspose.slides/mathnaryoperator/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.IMathNaryOperator](../../com.aspose.slides/imathnaryoperator), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathNaryOperator extends MathElementBase implements IMathNaryOperator, IHasControlCharacterProperties
```

एक N-ary गणितीय वस्तु को निर्दिष्ट करता है, जैसे Summation और Integral। इसमें एक ऑपरेटर, एक बेस (या ऑपरेन्ड), और वैकल्पिक ऊपरी और निचली सीमाएँ शामिल हैं। N-ary ऑपरेटर के उदाहरण हैं: Summation, Union, Intersection, Integral

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
```
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | MathNaryOperator वर्ग का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | MathNaryOperator वर्ग का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#MathNaryOperator-char-com.aspose.slides.IMathElement-) | MathNaryOperator वर्ग का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getBase()](#getBase--) | बेस तर्क |
| [getSubscript()](#getSubscript--) | उपस्क्रिप्ट तर्क निर्दिष्ट करता है जो, उदाहरण के लिए, इंटीग्रल के मामले में, निचली सीमा सेट करता है |
| [getSuperscript()](#getSuperscript--) | सुपरसक्रिप्ट तर्क निर्दिष्ट करता है जो, उदाहरण के लिए, इंटीग्रल के मामले में, ऊपरी सीमा सेट करता है |
| [getOperator()](#getOperator--) | Nary ऑपरेटर कैरेक्टर उदाहरण के लिए: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | Nary ऑपरेटर कैरेक्टर उदाहरण के लिए: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | सीमाओं का स्थान (उपस्क्रिप्ट और सुपरसक्रिप्ट) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | सीमाओं का स्थान (उपस्क्रिप्ट और सुपरसक्रिप्ट) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | ऑपरेटर कैरेक्टर लम्बवत रूप से बढ़ता है ताकि उसका ऑपरेण्ड ऊँचाई से मेल खाए |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | ऑपरेटर कैरेक्टर लम्बवत रूप से बढ़ता है ताकि उसका ऑपरेण्ड ऊँचाई से मेल खाए |
| [getHideSubscript()](#getHideSubscript--) | उपस्क्रिप्ट छिपाएँ |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | उपस्क्रिप्ट छिपाएँ |
| [getHideSuperscript()](#getHideSuperscript--) | सुपरसक्रिप्ट छिपाएँ |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | सुपरसक्रिप्ट छिपाएँ |
| [getChildren()](#getChildren--) | संतान तत्व प्राप्त करें |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | कंट्रोल कैरेक्टर प्रॉपर्टीज़ |
### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```

MathNaryOperator वर्ग का एक नया इंस्टेंस इनिशियलाइज़ करता है।

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i=0"), new MathematicalText("\ud835\udc5b"));
> ```

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

MathNaryOperator वर्ग का एक नया इंस्टेंस इनिशियलाइज़ करता है।

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i"));
> ```

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

MathNaryOperator वर्ग का एक नया इंस्टेंस इनिशियलाइज़ करता है।

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"));
> ```

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
```

**रिटर्न:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```

उपस्क्रिप्ट तर्क निर्दिष्ट करता है जो, उदाहरण के लिए, इंटीग्रल के मामले में, निचली सीमा सेट करता है

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
> ```

**रिटर्न:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```

सुपरसक्रिप्ट तर्क निर्दिष्ट करता है जो, उदाहरण के लिए, इंटीग्रल के मामले में, ऊपरी सीमा सेट करता है

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**रिटर्न:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperator() {#getOperator--}
```
public final char getOperator()
```

Nary ऑपरेटर कैरेक्टर उदाहरण के लिए: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**रिटर्न:**
char
### setOperator(char value) {#setOperator-char-}
```
public final void setOperator(char value)
```

Nary ऑपरेटर कैरेक्टर उदाहरण के लिए: '\\u2211', '\\u222b'

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

सीमाओं का स्थान (उपस्क्रिप्ट और सुपरसक्रिप्ट)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**रिटर्न:**
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public final void setLimitLocation(int value)
```

सीमाओं का स्थान (उपस्क्रिप्ट और सुपरसक्रिप्ट)

--------------------

> ```
> उदाहरण:
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

ऑपरेटर कैरेक्टर लम्बवत रूप से बढ़ता है ताकि उसका ऑपरेण्ड ऊँचाई से मेल खाए

--------------------

> ```
> उदाहरण:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**रिटर्न:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```

ऑपरेटर कैरेक्टर लम्बवत रूप से बढ़ता है ताकि उसका ऑपरेण्ड ऊँचाई से मेल खाए

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

उपस्क्रिप्ट छिपाएँ

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**रिटर्न:**
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public final void setHideSubscript(boolean value)
```

उपस्क्रिप्ट छिपाएँ

--------------------

> ```
> उदाहरण:
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

सुपरसक्रिप्ट छिपाएँ

--------------------

> ```
> उदाहरण:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**रिटर्न:**
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public final void setHideSuperscript(boolean value)
```

सुपरसक्रिप्ट छिपाएँ

--------------------

> ```
> उदाहरण:
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

संतान तत्व प्राप्त करें

**रिटर्न:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

कंट्रोल कैरेक्टर प्रॉपर्टीज़

**रिटर्न:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps