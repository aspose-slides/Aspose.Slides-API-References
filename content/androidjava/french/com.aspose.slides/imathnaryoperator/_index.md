---
title: IMathNaryOperator
second_title: Aspose.Slides pour Android via la référence API Java
description: Spécifie un objet mathématique n-aire tel que Summation et Integral.
type: docs
url: /fr/com.aspose.slides/imathnaryoperator/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), [com.aspose.slides.IMathNaryOperatorProperties](../../com.aspose.slides/imathnaryoperatorproperties)
```
public interface IMathNaryOperator extends IMathElement, IMathNaryOperatorProperties
```

Spécifie un objet mathématique n-aire, tel que Summation et Integral. Il se compose d'un opérateur, d'une base (ou opérande), et de limites supérieures et inférieures facultatives. Des exemples d'opérateurs n-aires sont : Summation, Union, Intersection, Integral

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
> ```

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
> ```

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()

Spécifie un argument de superscript qui, par exemple, dans le cas d'un intégral, définit la limite supérieure

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**Renvoie :**
[IMathElement](../../com.aspose.slides/imathelement)