---
title: IMathNaryOperator
second_title: Aspose.Slides pro Java API Reference
description: Specifikuje N-ární matematický objekt, jako je součet a integrál.
type: docs
url: /cs/com.aspose.slides/imathnaryoperator/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), [com.aspose.slides.IMathNaryOperatorProperties](../../com.aspose.slides/imathnaryoperatorproperties)
```
public interface IMathNaryOperator extends IMathElement, IMathNaryOperatorProperties
```

Specifikuje N-ární matematický objekt, jako je součet a integrál. Skládá se z operátoru, základny (nebo operandu) a volitelných horních a dolních mezí. Příklady N-árních operátorů jsou: Summation, Union, Intersection, Integral

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
| [getSubscript()](#getSubscript--) | Specifikuje argument dolního indexu, který například v případě integrálu nastaví dolní mez |
| [getSuperscript()](#getSuperscript--) | Specifikuje argument horního indexu, který například v případě integrálu nastaví horní mez |
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
> ```

**Vrací:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```

Specifikuje argument dolního indexu, který například v případě integrálu nastaví dolní mez

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

Specifikuje argument horního indexu, který například v případě integrálu nastaví horní mez

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**Vrací:**
[IMathElement](../../com.aspose.slides/imathelement)