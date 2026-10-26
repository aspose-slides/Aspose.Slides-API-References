---
title: IMathNaryOperator
second_title: Aspose.Slides for Java API 參考
description: 指定一個 N 元數學物件，例如 Summation 與 Integral。
type: docs
url: /zh-hant/com.aspose.slides/imathnaryoperator/
---
**所有已實作的介面：**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), [com.aspose.slides.IMathNaryOperatorProperties](../../com.aspose.slides/imathnaryoperatorproperties)
```
public interface IMathNaryOperator extends IMathElement, IMathNaryOperatorProperties
```

指定一個 N 元數學物件，例如求和與積分。它由運算子、基底（或運算元）以及可選的上、下限組成。N 元運算子的例子包括：Summation、Union、Intersection、Integral

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
```
## 方法

| 方法 | 說明 |
| --- | --- |
| [getBase()](#getBase--) | 基底參數 |
| [getSubscript()](#getSubscript--) | 指定下標參數，例如在積分的情況下，設定下限 |
| [getSuperscript()](#getSuperscript--) | 指定上標參數，例如在積分的情況下，設定上限 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

基底參數

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement baseArg = naryOperator.getBase();
```

**傳回：**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```

指定下標參數，例如在積分的情況下，設定下限

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
> ```

**傳回：**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```

指定上標參數，例如在積分的情況下，設定上限

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**傳回：**
[IMathElement](../../com.aspose.slides/imathelement)