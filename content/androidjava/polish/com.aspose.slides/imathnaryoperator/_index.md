---
title: IMathNaryOperator
second_title: Aspose.Slides dla Androida - odniesienie do API Java
description: Określa obiekt matematyczny N-ary, taki jak Sumowanie i Całka.
type: docs
url: /pl/com.aspose.slides/imathnaryoperator/
---
**Wszystkie implementowane interfejsy:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), [com.aspose.slides.IMathNaryOperatorProperties](../../com.aspose.slides/imathnaryoperatorproperties)
```
public interface IMathNaryOperator extends IMathElement, IMathNaryOperatorProperties
```

Określa obiekt matematyczny N-ary, taki jak Sumowanie i Całka. Składa się z operatora, bazy (lub operand) oraz opcjonalnych górnych i dolnych limitów. Przykłady operatorów N-ary to: Sumowanie, Suma, Przecięcie, Całka

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
> ```
## Metody

| Metoda | Opis |
| --- | --- |
| [getBase()](#getBase--) | Argument bazowy |
| [getSubscript()](#getSubscript--) | Określa argument indeksu dolnego, który na przykład w przypadku całki ustawia dolną granicę |
| [getSuperscript()](#getSuperscript--) | Określa argument indeksu górnego, który na przykład w przypadku całki ustawia górną granicę |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Argument bazowy

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement baseArg = naryOperator.getBase();
> ```

**Zwraca:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```

Określa argument indeksu dolnego, który na przykład w przypadku całki ustawia dolną granicę

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
> ```

**Zwraca:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```

Określa argument indeksu górnego, który na przykład w przypadku całki ustawia górną granicę

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**Zwraca:**
[IMathElement](../../com.aspose.slides/imathelement)