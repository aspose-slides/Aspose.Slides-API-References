---
title: IMathNaryOperatorProperties
second_title: Aspose.Slides for Java API Reference
description: Specifies properties of IMathNaryOperator
type: docs
url: /hi/com.aspose.slides/imathnaryoperatorproperties/
---```
public interface IMathNaryOperatorProperties
```

IMathNaryOperator की प्रॉपर्टी को निर्दिष्ट करता है
## मेथड

| मेथड | विवरण |
| --- | --- |
| [getOperator()](#getOperator--) | Nary ऑपरेटर कैरेक्टर, उदाहरण: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | Nary ऑपरेटर कैरेक्टर, उदाहरण: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | सीमा की स्थिति (सबस्क्रिप्ट और सुपरस्क्रिप्ट) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | सीमा की स्थिति (सबस्क्रिप्ट और सुपरस्क्रिप्ट) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | ऑपरेटर कैरेक्टर अपने ऑपरेण्ड की ऊँचाई के अनुसार लंबवत बढ़ता है |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | ऑपरेटर कैरेक्टर अपने ऑपरेण्ड की ऊँचाई के अनुसार लंबवत बढ़ता है |
| [getHideSubscript()](#getHideSubscript--) | सबस्क्रिप्ट छुपाएँ |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | सबस्क्रिप्ट छुपाएँ |
| [getHideSuperscript()](#getHideSuperscript--) | सुपरस्क्रिप्ट छुपाएँ |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | सुपरस्क्रिप्ट छुपाएँ |
### getOperator() {#getOperator--}
```
public abstract char getOperator()
```


Nary ऑपरेटर कैरेक्टर, उदाहरण: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**वापसी मान:**  
char
### setOperator(char value) {#setOperator-char-}
```
public abstract void setOperator(char value)
```


Nary ऑपरेटर कैरेक्टर, उदाहरण: '\\u2211', '\\u222b'

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


सीमा की स्थिति (सबस्क्रिप्ट और सुपरस्क्रिप्ट)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**वापसी मान:**  
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public abstract void setLimitLocation(int value)
```


सीमा की स्थिति (सबस्क्रिप्ट और सुपरस्क्रिप्ट)

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


ऑपरेटर कैरेक्टर अपने ऑपरेण्ड की ऊँचाई के अनुसार लंबवत बढ़ता है

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**वापसी मान:**  
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```


ऑपरेटर कैरेक्टर अपने ऑपरेण्ड की ऊँचाई के अनुसार लंबवत बढ़ता है

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


सबस्क्रिप्ट छुपाएँ

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**वापसी मान:**  
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public abstract void setHideSubscript(boolean value)
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
public abstract boolean getHideSuperscript()
```


सुपरस्क्रिप्ट छुपाएँ

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**वापसी मान:**  
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public abstract void setHideSuperscript(boolean value)
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