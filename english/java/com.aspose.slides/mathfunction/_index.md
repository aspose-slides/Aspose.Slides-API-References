---
title: MathFunction
second_title: Aspose.Slides for Java API Reference
description:  Specifies a function of an argument.
type: docs
weight: 324
url: /java/com.aspose.slides/mathfunction/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**All Implemented Interfaces:**
[com.aspose.slides.IMathFunction](../../com.aspose.slides/imathfunction), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathFunction extends MathElementBase implements IMathFunction, IHasControlCharacterProperties
```

Specifies a function of an argument.

--------------------

> ```
> Example:
>  
>  MathFunction func = new MathFunction("sin", new MathematicalText("x"));
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [MathFunction(IMathElement funcName, IMathElement baseArgument)](#MathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Initializes a new instance of the MathFunction class. |
| [MathFunction(String funcName, IMathElement baseArgument)](#MathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Initializes a new instance of the MathFunction class. |
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Function name For example, function names are sin and cos |
| [getBase()](#getBase--) | Function Argument |
| [getChildren()](#getChildren--) | Get children elements |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
### MathFunction(IMathElement funcName, IMathElement baseArgument) {#MathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathFunction(IMathElement funcName, IMathElement baseArgument)
```


Initializes a new instance of the MathFunction class.

--------------------

> ```
> Example:
>  
>  MathFunction func = new MathFunction(new MathematicalText("sin"), new MathematicalText("x"));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) |  |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) |  |

### MathFunction(String funcName, IMathElement baseArgument) {#MathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public MathFunction(String funcName, IMathElement baseArgument)
```


Initializes a new instance of the MathFunction class.

--------------------

> ```
> Example:
>  
>  MathFunction func = new MathFunction("sin", new MathematicalText("x"));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| funcName | java.lang.String |  |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getName() {#getName--}
```
public final IMathElement getName()
```


Function name For example, function names are sin and cos

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement funcName = func.getName();
> ```

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Function Argument

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement base = func.getBase();
> ```

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Get children elements

**Returns:**
com.aspose.slides.IMathElement[] - Array of [IMathElement](../../com.aspose.slides/imathelement)
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Control Character Properties

**Returns:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
