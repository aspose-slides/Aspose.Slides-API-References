---
title: IMathNaryOperator
second_title: Aspose.Slides para Android via Referência da API Java
description: Especifica um objeto matemático N-ário, como Summation e Integral.
type: docs
url: /pt/com.aspose.slides/imathnaryoperator/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), [com.aspose.slides.IMathNaryOperatorProperties](../../com.aspose.slides/imathnaryoperatorproperties)
```
public interface IMathNaryOperator extends IMathElement, IMathNaryOperatorProperties
```

Especifica um objeto matemático N-ário, como Summation e Integral. Consiste em um operador, uma base (ou operando) e limites superior e inferior opcionais. Exemplos de operadores N-ários são: Summation, Union, Intersection, Integral

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
```
## Métodos

| Método | Descrição |
| --- | --- |
| [getBase()](#getBase--) | Argumento base |
| [getSubscript()](#getSubscript--) | Especifica um argumento de subscrito que, por exemplo, no caso de uma integral, define o limite inferior |
| [getSuperscript()](#getSuperscript--) | Especifica um argumento supersript que, por exemplo, no caso de uma integral, define o limite superior |
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
> ```

**Retorna:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```

Especifica um argumento de subscrito que, por exemplo, no caso de uma integral, define o limite inferior

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
> ```

**Retorna:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```

Especifica um argumento supersript que, por exemplo, no caso de uma integral, define o limite superior

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**Retorna:**
[IMathElement](../../com.aspose.slides/imathelement)