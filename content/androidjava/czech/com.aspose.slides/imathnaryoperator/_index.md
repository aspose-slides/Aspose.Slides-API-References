---
title: IMathNaryOperator
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Specifikuje N-ární matematický objekt, jako je Summation a Integral.
type: docs
url: /cs/com.aspose.slides/imathnaryoperator/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), [com.aspose.slides.IMathNaryOperatorProperties](../../com.aspose.slides/imathnaryoperatorproperties)
```
public interface IMathNaryOperator extends IMathElement, IMathNaryOperatorProperties
```

Specifikuje N-ární matematický objekt, například Summation a Integral. Skládá se z operátoru, základny (nebo operand) a volitelných horních a dolních mezí. Příklady N-árních operátorů jsou: Summation, Union, Intersection, Integral

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
> ```
## Metody

| Metoda | Popis |
| --- | --- |
| [getBase()](#getBase--) | Základní argument |
| [getSubscript()](#getSubscript--) | Určuje argument podindexu, který například v případě integrálu nastavuje dolní mez |
| [getSuperscript()](#getSuperscript--) | Určuje argument nadindexu, který například v případě integrálu nastavuje horní mez |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Základní argument

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement baseArg = naryOperator.getBase();
>  ```

**Vrací:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```

Určuje argument podindexu, který například v případě integrálu nastavuje dolní mez

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
> ```

**Vrací:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```

Určuje argument nadindexu, který například v případě integrálu nastavuje horní mez

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**Vrací:**
[IMathElement](../../com.aspose.slides/imathelement)