---
title: IMathNaryOperator
second_title: Aspose.Slides för Android via Java API-referens
description: Specificerar ett N-ärt matematiskt objekt såsom Summation och Integral.
type: docs
url: /sv/com.aspose.slides/imathnaryoperator/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), [com.aspose.slides.IMathNaryOperatorProperties](../../com.aspose.slides/imathnaryoperatorproperties)
```
public interface IMathNaryOperator extends IMathElement, IMathNaryOperatorProperties
```

Specificerar ett N-ärt matematiskt objekt, såsom Summation och Integral. Det består av en operator, en bas (eller operand), och valfria övre och nedre gränser. Exempel på N-ära operatorer är: Summation, Union, Intersection, Integral

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
> ```
## Metoder

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Basargument |
| [getSubscript()](#getSubscript--) | Specificerar ett indexargument som exempelvis i fallet med en integral sätter den nedre gränsen |
| [getSuperscript()](#getSuperscript--) | Specificerar ett upphöjningsargument som exempelvis i fallet med en integral sätter den övre gränsen |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Basargument

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement baseArg = naryOperator.getBase();
>  ```

**Returnerar:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```

Specificerar ett indexargument som exempelvis i fallet med en integral sätter den nedre gränsen

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
> ```

**Returnerar:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```

Specificerar ett upphöjningsargument som exempelvis i fallet med en integral sätter den övre gränsen

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**Returnerar:**
[IMathElement](../../com.aspose.slides/imathelement)