---
title: IMathNaryOperator
second_title: Aspose.Slides voor Java API-referentie
description: Specificeert een N-ary wiskundig object, zoals Summation en Integral.
type: docs
url: /nl/com.aspose.slides/imathnaryoperator/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), [com.aspose.slides.IMathNaryOperatorProperties](../../com.aspose.slides/imathnaryoperatorproperties)
```
public interface IMathNaryOperator extends IMathElement, IMathNaryOperatorProperties
```

Specificeert een N-ary wiskundig object, zoals Summation en Integral. Het bestaat uit een operator, een basis (of operand), en optionele boven- en onderlimieten. Voorbeelden van N-ary operatoren zijn: Summation, Union, Intersection, Integral

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
```
## Methodes

| Methode | Beschrijving |
| --- | --- |
| [getBase()](#getBase--) | Basisargument |
| [getSubscript()](#getSubscript--) | Specificeert een subscriptargument dat bijvoorbeeld, in het geval van een integral, de onderlimiet instelt |
| [getSuperscript()](#getSuperscript--) | Specificeert een superscriptargument dat bijvoorbeeld, in het geval van een integral, de bovengrens instelt |
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

**Retourneert:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```


Specificeert een subscriptargument dat bijvoorbeeld, in het geval van een integral, de onderlimiet instelt

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
> ```

**Retourneert:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```


Specificeert een superscriptargument dat bijvoorbeeld, in het geval van een integral, de bovengrens instelt

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**Retourneert:**
[IMathElement](../../com.aspose.slides/imathelement)