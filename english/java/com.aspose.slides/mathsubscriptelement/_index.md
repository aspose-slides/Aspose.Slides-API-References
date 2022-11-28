---
title: MathSubscriptElement
second_title: Aspose.Slides for Java API Reference
description: Specifies the subscript object which consists of a base  and a reduced-size subscript placed below and to the right.
type: docs
weight: 353
url: /java/com.aspose.slides/mathsubscriptelement/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**All Implemented Interfaces:**
[com.aspose.slides.IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
```
public final class MathSubscriptElement extends BaseScript implements IMathSubscriptElement
```

Specifies the subscript object, which consists of a base and a reduced-size subscript placed below and to the right.

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [MathSubscriptElement(IMathElement baseArg, IMathElement subScript)](#MathSubscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Initializes a new instance of the MathSubscriptElement class. |
## Methods

| Method | Description |
| --- | --- |
| [getSubscript()](#getSubscript--) | Subscript |
| [getChildren()](#getChildren--) | Get children elements |
### MathSubscriptElement(IMathElement baseArg, IMathElement subScript) {#MathSubscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathSubscriptElement(IMathElement baseArg, IMathElement subScript)
```


Initializes a new instance of the MathSubscriptElement class.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| subScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
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
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Get children elements

**Returns:**
com.aspose.slides.IMathElement[]
