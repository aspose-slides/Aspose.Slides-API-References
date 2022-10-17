---
title: IMathFunction
second_title: Aspose.Slides for Java API Reference
description:  Specifies a function of an argument.
type: docs
weight: 896
url: /java/com.aspose.slides/imathfunction/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFunction extends IMathElement
```

Specifies a function of an argument.

--------------------

> ```
> Example:
>  
>  IMathFunction sinX = new MathematicalText("sin").function("x");
> ```
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Function name For example, function names are sin and cos |
| [getBase()](#getBase--) | Function Argument |
### getName() {#getName--}
```
public abstract IMathElement getName()
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
public abstract IMathElement getBase()
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
