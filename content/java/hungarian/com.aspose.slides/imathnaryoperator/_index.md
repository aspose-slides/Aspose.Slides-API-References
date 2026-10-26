---
title: IMathNaryOperator
second_title: Aspose.Slides Java API Referencia
description: Egy N-értelmű matematikai objektumot határoz meg, például a Summation-t és az Integral-t.
type: docs
url: /hu/com.aspose.slides/imathnaryoperator/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), [com.aspose.slides.IMathNaryOperatorProperties](../../com.aspose.slides/imathnaryoperatorproperties)
```
public interface IMathNaryOperator extends IMathElement, IMathNaryOperatorProperties
```

Egy N-értelmű matematikai objektumot specifikál, például Summation és Integral. Egy operátorból, egy alapból (vagy operandusból) és opcionális felső és alsó határból áll. Az N-értelmű operátorok példái: Summation, Union, Intersection, Integral

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  ```
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getBase()](#getBase--) | Alap argumentum |
| [getSubscript()](#getSubscript--) | Egy alsó index argumentumot specifikál, amely például integrál esetén beállítja az alsó határt |
| [getSuperscript()](#getSuperscript--) | Egy felső index argumentumot specifikál, amely például integrál esetén beállítja a felső határt |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Alap argumentum

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement baseArg = naryOperator.getBase();
>  ```


**Visszatér:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```


Egy alsó index argumentumot specifikál, amely például integrál esetén beállítja az alsó határt

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
>  ```

**Visszatér:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```


Egy felső index argumentumot specifikál, amely például integrál esetén beállítja a felső határt

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
>  ```

**Visszatér:**
[IMathElement](../../com.aspose.slides/imathelement)