---
title: IMathNaryOperator
second_title: Java API リファレンスによる Android 向け Aspose.Slides
description: Summation や Integral などの N 元数学オブジェクトを指定します。
type: docs
url: /ja/com.aspose.slides/imathnaryoperator/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), [com.aspose.slides.IMathNaryOperatorProperties](../../com.aspose.slides/imathnaryoperatorproperties)
```
public interface IMathNaryOperator extends IMathElement, IMathNaryOperatorProperties
```

N元の数学オブジェクト（例：Summation や Integral）を指定します。演算子、ベース（またはオペランド）、およびオプションの上限と下限から構成されます。N元演算子の例としては、Summation、Union、Intersection、Integral があります。

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
> ```
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBase()](#getBase--) | ベース引数 |
| [getSubscript()](#getSubscript--) | 例えば integral の場合に下限を設定する下付き引数を指定します |
| [getSuperscript()](#getSuperscript--) | 例えば integral の場合に上限を設定する上付き引数を指定します |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

ベース引数

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement baseArg = naryOperator.getBase();
>  ```


**戻り値:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```

例えば integral の場合に下限を設定する下付き引数を指定します

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
>  ```

**戻り値:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```

例えば integral の場合に上限を設定する上付き引数を指定します

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**戻り値:**
[IMathElement](../../com.aspose.slides/imathelement)