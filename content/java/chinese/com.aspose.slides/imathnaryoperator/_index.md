---
title: IMathNaryOperator
second_title: Aspose.Slides 的 Java API 参考
description: 指定一个 N 元数学对象，例如 Summation 和 Integral。
type: docs
url: /zh/com.aspose.slides/imathnaryoperator/
---
**所有已实现的接口：**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), [com.aspose.slides.IMathNaryOperatorProperties](../../com.aspose.slides/imathnaryoperatorproperties)
```
public interface IMathNaryOperator extends IMathElement, IMathNaryOperatorProperties
```

指定一个 N 元数学对象，例如 Summation 和 Integral。它由运算符、基数（或操作数）以及可选的上限和下限组成。N 元运算符的示例有：Summation、Union、Intersection、Integral

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
> ```
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBase()](#getBase--) | 基数参数 |
| [getSubscript()](#getSubscript--) | 指定下标参数，例如在积分的情况下设置下限 |
| [getSuperscript()](#getSuperscript--) | 指定上标参数，例如在积分的情况下设置上限 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

基数参数

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement baseArg = naryOperator.getBase();
>  ```

**返回：**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```

指定下标参数，例如在积分的情况下设置下限

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
> ```

**返回：**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```

指定上标参数，例如在积分的情况下设置上限

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**返回：**
[IMathElement](../../com.aspose.slides/imathelement)