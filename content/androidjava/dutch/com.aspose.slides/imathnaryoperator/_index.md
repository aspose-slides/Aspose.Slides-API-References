---
title: IMathNaryOperator
second_title: Aspose.Slides voor Android via Java API-referentie
description: Specificeert een N-aire wiskundig object, zoals Summation en Integral.
type: docs
url: /nl/com.aspose.slides/imathnaryoperator/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), [com.aspose.slides.IMathNaryOperatorProperties](../../com.aspose.slides/imathnaryoperatorproperties)
```
public interface IMathNaryOperator extends IMathElement, IMathNaryOperatorProperties
```

Specificeert een N-aire wiskundig object, zoals Summation en Integral. Het bestaat uit een operator, een basis (of operand), en optionele boven- en ondergrenzen. Voorbeelden van N-aire operatoren zijn: Summation, Union, Intersection, Integral

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  ```

## Methodes

| Methode | Beschrijving |
| --- | --- |
| [getBase()](#getBase--) | Basisargument |
| [getSubscript()](#getSubscript--) | Geeft een subscript-argument op dat, bijvoorbeeld bij een integraal, de ondergrens instelt |
| [getSuperscript()](#getSuperscript--) | Geeft een superscript-argument op dat, bijvoorbeeld bij een integraal, de bovengrens instelt |
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
>  ```


**Retour:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```


Geeft een subscript-argument op dat, bijvoorbeeld bij een integraal, de ondergrens instelt

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
>  ```


**Retour:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```


Geeft een superscript-argument op dat, bijvoorbeeld bij een integraal, de bovengrens instelt

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
>  ```


**Retour:**
[IMathElement](../../com.aspose.slides/imathelement)