---
title: IMathSuperscriptElement
second_title: Aspose.Slides for Android via Java API 参考
description: 指定上标对象，该对象由基底和一个缩小的上标组成，位于右上方
type: docs
url: /zh/com.aspose.slides/imathsuperscriptelement/
---
**所有实现的接口：**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSuperscriptElement extends IMathElement
```

指定上标对象，该对象由基底和一个缩小的上标组成，位于右上方

--------------------

> ```
> Example:
>  
>  IMathSuperscriptElement superscriptElement = new MathematicalText("N").setSuperscript("i");
> ```
## Methods

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getSuperscript()](#getSuperscript--) | Superscript |
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
>  IMathElement superscript = new MathematicalText("i");
>  IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, subscript);
>  IMathElement baseElem = superscriptElement.getBase();
> ```

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()


Superscript

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
>  IMathElement super = superscriptElement.getSuperscript();
>  ```

**返回：**
[IMathElement](../../com.aspose.slides/imathelement)