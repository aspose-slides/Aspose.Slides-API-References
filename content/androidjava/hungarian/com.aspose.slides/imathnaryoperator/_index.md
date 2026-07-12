---
title: IMathNaryOperator
second_title: Aspose.Slides for Android a Java API referencia
description: N-ary matematikai objektumot határoz meg, például Summation és Integral.
type: docs
url: /hu/com.aspose.slides/imathnaryoperator/
---
**Minden implementált interfész:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), [com.aspose.slides.IMathNaryOperatorProperties](../../com.aspose.slides/imathnaryoperatorproperties)
```
public interface IMathNaryOperator extends IMathElement, IMathNaryOperatorProperties
```

N-ary matematikai objektumot határoz meg, például Summation és Integral. Operátorból, egy bázisból (vagy operandusból) és opcionális felső és alsó határból áll. N-ary operátorok példái: Summation, Union, Intersection, Integral

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
> ```
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getBase()](#getBase--) | Alap argumentum |
| [getSubscript()](#getSubscript--) | Megad egy alsó index argumentumot, amely például integrál esetén az alsó határt állítja be |
| [getSuperscript()](#getSuperscript--) | Megad egy felső index argumentumot, amely például integrál esetén a felső határt állítja be |
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
> ```

**Visszatér:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```


Megad egy alsó index argumentumot, amely például integrál esetén az alsó határt állítja be

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
> ```

**Visszatér:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```


Megad egy felső index argumentumot, amely például integrál esetén a felső határt állítja be

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**Visszatér:**
[IMathElement](../../com.aspose.slides/imathelement)