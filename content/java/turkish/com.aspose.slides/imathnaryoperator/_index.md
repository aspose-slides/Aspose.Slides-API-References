---
title: IMathNaryOperator
second_title: Aspose.Slides for Java API Referansı
description: Summation ve Integral gibi N-ary bir matematiksel nesneyi belirtir.
type: docs
url: /tr/com.aspose.slides/imathnaryoperator/
---
**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), [com.aspose.slides.IMathNaryOperatorProperties](../../com.aspose.slides/imathnaryoperatorproperties)
```
public interface IMathNaryOperator extends IMathElement, IMathNaryOperatorProperties
```

N-ary bir matematiksel nesneyi belirtir, örneğin Summation ve Integral. Bir operatör, bir temel (veya operand) ve isteğe bağlı üst ve alt limitlerden oluşur. N-ary operatör örnekleri şunlardır: Summation, Union, Intersection, Integral

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
> ```
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBase()](#getBase--) | Temel argüman |
| [getSubscript()](#getSubscript--) | Bir alt simge argümanını belirtir; örneğin, bir integral durumunda, alt sınırı ayarlar |
| [getSuperscript()](#getSuperscript--) | Bir üst simge argümanını belirtir; örneğin, bir integral durumunda, üst sınırı ayarlar |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Temel argüman

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement baseArg = naryOperator.getBase();
> ```

**Döndürür:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```


Bir alt simge argümanını belirtir; örneğin, bir integral durumunda, alt sınırı ayarlar

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
> ```

**Döndürür:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```


Bir üst simge argümanını belirtir; örneğin, bir integral durumunda, üst sınırı ayarlar

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**Döndürür:**
[IMathElement](../../com.aspose.slides/imathelement)