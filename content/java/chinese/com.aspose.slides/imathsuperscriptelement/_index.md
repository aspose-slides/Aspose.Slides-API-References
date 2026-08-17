---
title: IMathSuperscriptElement
second_title: Aspose.Slides for Java API 参考
description: 指定上标对象，由基对象和位于右上方的缩小尺寸上标组成
type: docs
url: /zh/com.aspose.slides/imathsuperscriptelement/
---
**所有已实现的接口：**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSuperscriptElement extends IMathElement
```

指定上标对象，由基线和位于右上方的缩小尺寸上标组成

--------------------

> ```
> Example:
>  
>  IMathSuperscriptElement superscriptElement = new MathematicalText("N").setSuperscript("i");
```
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBase()](#getBase--) | 基参数 |
| [getSuperscript()](#getSuperscript--) | 上标 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


基参数

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, subscript);
>  IMathElement baseElem = superscriptElement.getBase();
> ```

**返回：**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```


上标

--------------------

> ```
> Example:
>  
>  IMMathElement baseElement = new MathematicalText("X");
>  IMMathElement superscript = new MathematicalText("i");
>  IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
>  IMathElement super = superscriptElement.getSuperscript();
> ```

**返回：**
[IMathElement](../../com.aspose.slides/imathelement)