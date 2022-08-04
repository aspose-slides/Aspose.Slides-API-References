---
title: MathNaryOperator
second_title: Aspose.Sildes for Java API Reference
description: p
 Specifies an N-ary mathematical object such as Summation and Integral.
type: docs
weight: 339
url: /java/com.aspose.slides/mathnaryoperator/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**All Implemented Interfaces:**
[com.aspose.slides.IMathNaryOperator](../../com.aspose.slides/imathnaryoperator), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathNaryOperator extends MathElementBase implements IMathNaryOperator, IHasControlCharacterProperties
```

Specifies an N-ary mathematical object, such as Summation and Integral. It consists of an operator, a base (or operand), and optional upper and lower limits. Examples of N-ary operators are: Summation, Union, Intersection, Integral

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [MathNaryOperator(IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit, IMathNaryOperatorProperties properties)](#MathNaryOperator-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathNaryOperatorProperties-) | Initializes a new instance of the MathNaryOperator class. |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Initializes a new instance of the MathNaryOperator class. |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Initializes a new instance of the MathNaryOperator class. |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#MathNaryOperator-char-com.aspose.slides.IMathElement-) | Initializes a new instance of the MathNaryOperator class. |
## Methods

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getSubscript()](#getSubscript--) | Specifies a subscript argument that, for example, in the case of an integral, sets the lower limit |
| [getSuperscript()](#getSuperscript--) | Specifies a supersript argument that, for example, in the case of an integral, sets the upper limit |
| [getOperator()](#getOperator--) | Nary Operator Character For example: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | Nary Operator Character For example: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | The location of limits (subscript and superscript) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | The location of limits (subscript and superscript) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Operator Character grows vertically to match its operand height |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Operator Character grows vertically to match its operand height |
| [getHideSubscript()](#getHideSubscript--) | Hide Subscript |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | Hide Subscript |
| [getHideSuperscript()](#getHideSuperscript--) | Hide Superscript |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | Hide Superscript |
| [getChildren()](#getChildren--) | Get children elements |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
### MathNaryOperator(IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit, IMathNaryOperatorProperties properties) {#MathNaryOperator-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathNaryOperatorProperties-}
```
 MathNaryOperator(IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit, IMathNaryOperatorProperties properties)
```


Initializes a new instance of the MathNaryOperator class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) |  |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) |  |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) |  |
| properties | [IMathNaryOperatorProperties](../../com.aspose.slides/imathnaryoperatorproperties) |  |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```


Initializes a new instance of the MathNaryOperator class.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i=0"), new MathematicalText("\ud835\udc5b"));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| operatorSymbol | char | Nary operator symbol |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Base argument |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Lower limit |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Upper limit |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```


Initializes a new instance of the MathNaryOperator class.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i"));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| operatorSymbol | char | Nary operator symbol |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Base argument |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Lower limit |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#MathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```


Initializes a new instance of the MathNaryOperator class.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| operatorSymbol | char | Nary operator symbol |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Base argument |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Base argument

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement baseArg = naryOperator.getBase();
> ```

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```


Specifies a subscript argument that, for example, in the case of an integral, sets the lower limit

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
> ```

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```


Specifies a supersript argument that, for example, in the case of an integral, sets the upper limit

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperator() {#getOperator--}
```
public final char getOperator()
```


Nary Operator Character For example: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Returns:**
char
### setOperator(char value) {#setOperator-char-}
```
public final void setOperator(char value)
```


Nary Operator Character For example: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |

### getLimitLocation() {#getLimitLocation--}
```
public final int getLimitLocation()
```


The location of limits (subscript and superscript)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Returns:**
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public final void setLimitLocation(int value)
```


The location of limits (subscript and superscript)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public final boolean getGrowToMatchOperandHeight()
```


Operator Character grows vertically to match its operand height

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Returns:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```


Operator Character grows vertically to match its operand height

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideSubscript() {#getHideSubscript--}
```
public final boolean getHideSubscript()
```


Hide Subscript

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Returns:**
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public final void setHideSubscript(boolean value)
```


Hide Subscript

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideSuperscript() {#getHideSuperscript--}
```
public final boolean getHideSuperscript()
```


Hide Superscript

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Returns:**
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public final void setHideSuperscript(boolean value)
```


Hide Superscript

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Get children elements

**Returns:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Control Character Properties

**Returns:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
