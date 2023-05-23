---
title: IMathRadical
second_title: Aspose.Slides for Android via Java API Reference
description: Specifies the radical function consisting of a base and an optional degree.
type: docs
weight: 916
url: /androidjava/com.aspose.slides/imathradical/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRadical extends IMathElement
```

Specifies the radical function, consisting of a base, and an optional degree. Example of radical object is \\u221a\\ud835\\udc65.

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // cube root
> ```
## Methods

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getDegree()](#getDegree--) | Degree argument |
| [getHideDegree()](#getHideDegree--) | Hide degree When is true, the degree is not shown, as in \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | Hide degree When is true, the degree is not shown, as in \\u221a\\ud835\\udc65 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Base argument

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // cube root
>  IMathElement baseElem = radical.getBase();
> ```

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public abstract IMathElement getDegree()
```


Degree argument

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // cube root
>  IMathElement degreeElem = radical.getDegree();
> ```

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public abstract boolean getHideDegree()
```


Hide degree When is true, the degree is not shown, as in \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // cube root
>  radical.setHideDegree(true);
> ```

**Returns:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public abstract void setHideDegree(boolean value)
```


Hide degree When is true, the degree is not shown, as in \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // cube root
>  radical.setHideDegree(true);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

