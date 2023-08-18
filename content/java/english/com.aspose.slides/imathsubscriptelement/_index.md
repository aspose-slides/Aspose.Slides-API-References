---
title: IMathSubscriptElement
second_title: Aspose.Slides for Java API Reference
description: Specifies the subscript object which consists of a base  and a reduced-size subscript placed below and to the right.
type: docs
weight: 919
url: /com.aspose.slides/imathsubscriptelement/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSubscriptElement extends IMathElement
```

Specifies the subscript object, which consists of a base and a reduced-size subscript placed below and to the right.

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
> ```
## Methods

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getSubscript()](#getSubscript--) | Subscript |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Base argument

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement baseElem = subscriptElement.getBase();
> ```

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```


Subscript

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement sub = subscriptElement.getSubscript();
> ```

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
