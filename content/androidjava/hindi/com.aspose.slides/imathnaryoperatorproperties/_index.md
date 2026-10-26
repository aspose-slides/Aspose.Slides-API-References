---
title: IMathNaryOperatorProperties
second_title: Aspose.Slides Android के लिए Java API संदर्भ
description: IMathNaryOperator के गुण निर्दिष्ट करता है
type: docs
url: /hi/com.aspose.slides/imathnaryoperatorproperties/
---```
public interface IMathNaryOperatorProperties
```

IMathNaryOperator के गुण निर्दिष्ट करता है
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getOperator()](#getOperator--) | Nary ऑपरेटर अक्षर के लिए उदाहरण: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | Nary ऑपरेटर अक्षर के लिए उदाहरण: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | सीमाओं (सबस्क्रिप्ट और सुपरस्क्रिप्ट) का स्थान |
| [setLimitLocation(int value)](#setLimitLocation-int-) | सीमाओं (सबस्क्रिप्ट और सुपरस्क्रिप्ट) का स्थान |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | ऑपरेटर अक्षर उसके ऑपरेण्ड की ऊँचाई से मेल खाने के लिये लंबवत बढ़ता है |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | ऑपरेटर अक्षर उसके ऑपरेण्ड की ऊँचाई से मेल खाने के लिये लंबवत बढ़ता है |
| [getHideSubscript()](#getHideSubscript--) | सबस्क्रिप्ट छिपाएँ |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | सबस्क्रिप्ट छिपाएँ |
| [getHideSuperscript()](#getHideSuperscript--) | सुपरस्क्रिप्ट छिपाएँ |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | सुपरस्क्रिप्ट छिपाएँ |
### getOperator() {#getOperator--}
```
public abstract char getOperator()
```

Nary ऑपरेटर अक्षर के लिए उदाहरण: '\\u2211', '\\u222b'

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
public abstract void setOperator(char value)
```

Nary ऑपरेटर अक्षर के लिए उदाहरण: '\\u2211', '\\u222b'

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
public abstract int getLimitLocation()
```

सीमाओं (सबस्क्रिप्ट और सुपरस्क्रिप्ट) का स्थान

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
public abstract void setLimitLocation(int value)
```

सीमाओं (सबस्क्रिप्ट और सुपरस्क्रिप्ट) का स्थान

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
public abstract boolean getGrowToMatchOperandHeight()
```

ऑपरेटर अक्षर उसके ऑपरेण्ड की ऊँचाई से मेल खाने के लिये लंबवत बढ़ता है

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**रिटर्न:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```

ऑपरेटर अक्षर उसके ऑपरेण्ड की ऊँचाई से मेल खाने के लिये लंबवत बढ़ता है

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
public abstract boolean getHideSubscript()
```

सबस्क्रिप्ट छिपाएँ

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
public abstract void setHideSubscript(boolean value)
```

सबस्क्रिप्ट छिपाएँ

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
public abstract boolean getHideSuperscript()
```

सुपरस्क्रिप्ट छिपाएँ

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**रिटर्न:**
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public abstract void setHideSuperscript(boolean value)
```

सुपरस्क्रिप्ट छिपाएँ

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