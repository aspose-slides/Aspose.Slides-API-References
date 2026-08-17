---
title: MathSuperscriptElement
second_title: Aspose.Slides 的 Java API 参考
description: 指定上标对象，该对象由基底和位于右上方的缩小尺寸上标组成
type: docs
url: /zh/com.aspose.slides/mathsuperscriptelement/
---
**继承:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**所有实现的接口:**  
[com.aspose.slides.IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)  
```
public final class MathSuperscriptElement extends BaseScript implements IMathSuperscriptElement
```

指定上标对象，该对象由基底和位于右上方的缩小尺寸上标组成

--------------------

> ```
> Example:
>  
>  IMathSuperscriptElement superscriptElement = new MathematicalText("N").setSuperscript("i");
> ```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MathSuperscriptElement(IMathElement baseArg, IMathElement superScript)](#MathSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 初始化 MathSuperscriptElement 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getSuperscript()](#getSuperscript--) | 上标 |
| [getChildren()](#getChildren--) | 获取子元素 |
### MathSuperscriptElement(IMathElement baseArg, IMathElement superScript) {#MathSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathSuperscriptElement(IMathElement baseArg, IMathElement superScript)
```

初始化 MathSuperscriptElement 类的新实例。

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  MathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
> ```

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| superScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```

上标

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  MathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
>  IMathElement super = superscriptElement.getSuperscript();
> ```

**返回:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

获取子元素

**返回:**  
com.aspose.slides.IMathElement[]