---
title: IMathNaryOperator
second_title: Aspose.Slides para Android mediante la referencia de la API de Java
description: Especifica un objeto matemático N-ario, como Sumatoria e Integral.
type: docs
url: /es/com.aspose.slides/imathnaryoperator/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), [com.aspose.slides.IMathNaryOperatorProperties](../../com.aspose.slides/imathnaryoperatorproperties)
```
public interface IMathNaryOperator extends IMathElement, IMathNaryOperatorProperties
```

Especifica un objeto matemático N-ario, como Sumatoria e Integral. Consiste en un operador, una base (u operando) y límites superiores e inferiores opcionales. Ejemplos de operadores N-arios son: Sumatoria, Unión, Intersección, Integral

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
> ```
## Métodos

| Método | Descripción |
| --- | --- |
| [getBase()](#getBase--) | Argumento base |
| [getSubscript()](#getSubscript--) | Especifica un argumento de subíndice que, por ejemplo, en el caso de una integral, establece el límite inferior |
| [getSuperscript()](#getSuperscript--) | Especifica un argumento de superíndice que, por ejemplo, en el caso de una integral, establece el límite superior |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Argumento base

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement baseArg = naryOperator.getBase();
>  ```

**Devuelve:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```

Especifica un argumento de subíndice que, por ejemplo, en el caso de una integral, establece el límite inferior

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
>  ```

**Devuelve:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```

Especifica un argumento de superíndice que, por ejemplo, en el caso de una integral, establece el límite superior

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
>  ```

**Devuelve:**
[IMathElement](../../com.aspose.slides/imathelement)