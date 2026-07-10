---
title: IMathNaryOperator
second_title: 适用于 Android 的 Aspose.Slides Java API 参考
description: 指定一个 N 元数学对象，例如求和和积分。
type: docs
url: /zh/com.aspose.slides/imathnaryoperator/
---
**所有实现的接口：**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), [com.aspose.slides.IMathNaryOperatorProperties](../../com.aspose.slides/imathnaryoperatorproperties)
```
public interface IMathNaryOperator extends IMathElement, IMathNaryOperatorProperties
```

指定一个 N 元数学对象，例如 Summation 和 Integral。它由运算符、基数（或操作数）以及可选的上限和下限组成。N 元运算符的例子包括：Summation、Union、Intersection、Integral

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
> ```
## Methods

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getSubscript()](#getSubscript--) | Specifies a subscript argument that, for example, in the case of an integral, sets the lower limit |
| [getSuperscript()](#getSuperscript--) | Specifies a supersript argument that, for example, in the case of an integral, sets the upper limit |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Base argument

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement baseArg = naryOperator.getBase();
>  ```

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```

Specifies a subscript argument that, for example, in the case of an integral, sets the lower limit

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
>  ```

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()


指定一个上标参数，例如在 Integral 的情况下，用于设置上限

--------------------

> ```
> 示例：
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
>  ```

**返回值：**
[IMathElement](../../com.aspose.slides/imathelement)