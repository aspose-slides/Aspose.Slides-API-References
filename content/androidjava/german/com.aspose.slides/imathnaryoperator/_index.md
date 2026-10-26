---
title: IMathNaryOperator
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Beschreibt ein n-äres mathematisches Objekt wie Summation und Integral.
type: docs
url: /de/com.aspose.slides/imathnaryoperator/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), [com.aspose.slides.IMathNaryOperatorProperties](../../com.aspose.slides/imathnaryoperatorproperties)
```
public interface IMathNaryOperator extends IMathElement, IMathNaryOperatorProperties
```

Beschreibt ein n-äres mathematisches Objekt, wie Summation und Integral. Es besteht aus einem Operator, einer Basis (oder Operanden) und optionalen oberen und unteren Grenzen. Beispiele für n-äre Operatoren sind: Summation, Union, Intersection, Integral

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
```
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBase()](#getBase--) | Basisargument |
| [getSubscript()](#getSubscript--) | Gibt ein Unterschriftsargument an, das beispielsweise im Falle eines Integrals die untere Grenze festlegt |
| [getSuperscript()](#getSuperscript--) | Gibt ein Hochstellungsargument an, das beispielsweise im Falle eines Integrals die obere Grenze festlegt |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Basisargument

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement baseArg = naryOperator.getBase();
> ```

**Rückgabewert:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```

Gibt ein Unterschriftsargument an, das beispielsweise im Falle eines Integrals die untere Grenze festlegt

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
> ```

**Rückgabewert:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```

Gibt ein Hochstellungsargument an, das beispielsweise im Falle eines Integrals die obere Grenze festlegt

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**Rückgabewert:**
[IMathElement](../../com.aspose.slides/imathelement)