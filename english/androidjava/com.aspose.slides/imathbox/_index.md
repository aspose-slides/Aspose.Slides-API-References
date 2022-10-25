---
title: IMathBox
second_title: Aspose.Slides for Android via Java API Reference
description: Specifies the logical boxing packaging of mathematical element.
type: docs
weight: 889
url: /androidjava/com.aspose.slides/imathbox/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBox extends IMathElement
```

Specifies the logical boxing (packaging) of mathematical element. For example, a boxed object can serve as an operator emulator with or without an alignment point, serve as a line break point, or be grouped such as not to allow line breaks within. For example, the "==" operator should be boxed to prevent line breaks.

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
> ```
## Methods

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getOperatorEmulator()](#getOperatorEmulator--) | Operator Emulator. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Operator Emulator. |
| [getNoBreak()](#getNoBreak--) | No break. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | No break. |
| [getDifferential()](#getDifferential--) | Differential. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Differential. |
| [getAlignmentPoint()](#getAlignmentPoint--) | When true, this operator emulator serves as an alignment point; that is, designated alignment points in other equations can be aligned with it. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | When true, this operator emulator serves as an alignment point; that is, designated alignment points in other equations can be aligned with it. |
| [getExplicitBreak()](#getExplicitBreak--) | Explicit break specifies whether there is a line break at the start of the Box object, such that the line wraps at the start of the box object. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Explicit break specifies whether there is a line break at the start of the Box object, such that the line wraps at the start of the box object. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Base argument

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  IMathElement base = box.getBase();
> ```

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public abstract boolean getOperatorEmulator()
```


Operator Emulator. When true, the box and its contents behave as a single operator and inherit the properties of an operator. This means, for example, that the character can serve as a point for a line break and can be aligned to other operators. Operator Emulators are often used when one or more glyphs combine to form an operator, such as '=='. Default value: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**Returns:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public abstract void setOperatorEmulator(boolean value)
```


Operator Emulator. When true, the box and its contents behave as a single operator and inherit the properties of an operator. This means, for example, that the character can serve as a point for a line break and can be aligned to other operators. Operator Emulators are often used when one or more glyphs combine to form an operator, such as '=='. Default value: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public abstract boolean getNoBreak()
```


No break. This property specifies the "unbreakable" property on the object box. When true, no line breaks can occur within the box. This can be important for operator emulators that consist of more than one binary operator. When this element is not specified, breaks can occur inside box. Default: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**Returns:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public abstract void setNoBreak(boolean value)
```


No break. This property specifies the "unbreakable" property on the object box. When true, no line breaks can occur within the box. This can be important for operator emulators that consist of more than one binary operator. When this element is not specified, breaks can occur inside box. Default: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public abstract boolean getDifferential()
```


Differential. When true, the box acts as a differential (e.g., \\ud835\\udc51\\ud835\\udc65 in an integrand), and receives the appropriate horizontal spacing for the mathematical differential. Default: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**Returns:**
boolean
### setDifferential(boolean value) {#setDifferential-boolean-}
```
public abstract void setDifferential(boolean value)
```


Differential. When true, the box acts as a differential (e.g., \\ud835\\udc51\\ud835\\udc65 in an integrand), and receives the appropriate horizontal spacing for the mathematical differential. Default: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAlignmentPoint() {#getAlignmentPoint--}
```
public abstract boolean getAlignmentPoint()
```


When true, this operator emulator serves as an alignment point; that is, designated alignment points in other equations can be aligned with it. Default: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Returns:**
boolean
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public abstract void setAlignmentPoint(boolean value)
```


When true, this operator emulator serves as an alignment point; that is, designated alignment points in other equations can be aligned with it. Default: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getExplicitBreak() {#getExplicitBreak--}
```
public abstract byte getExplicitBreak()
```


Explicit break specifies whether there is a line break at the start of the Box object, such that the line wraps at the start of the box object. Specifies the number of the operator on the previous line of mathematical text which shall be used as the alignment point for the current line of mathematical text possible values: 1..255 Default: 0 (no explicit break)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Returns:**
byte
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public abstract void setExplicitBreak(byte value)
```


Explicit break specifies whether there is a line break at the start of the Box object, such that the line wraps at the start of the box object. Specifies the number of the operator on the previous line of mathematical text which shall be used as the alignment point for the current line of mathematical text possible values: 1..255 Default: 0 (no explicit break)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

