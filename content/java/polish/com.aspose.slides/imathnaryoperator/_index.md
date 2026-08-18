---
title: IMathNaryOperator
second_title: Aspose.Slides for Java – odniesienie API
description: Określa n-arny obiekt matematyczny, taki jak Summation i Integral.
type: docs
url: /pl/com.aspose.slides/imathnaryoperator/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), [com.aspose.slides.IMathNaryOperatorProperties](../../com.aspose.slides/imathnaryoperatorproperties)
```
public interface IMathNaryOperator extends IMathElement, IMathNaryOperatorProperties
```

Określa n-arny obiekt matematyczny, taki jak Summation i Integral. Składa się z operatora, podstawy (lub operanda) oraz opcjonalnych górnych i dolnych granic. Przykłady n-arnych operatorów to: Summation, Union, Intersection, Integral

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
> ```
## Metody

| Metoda | Opis |
| --- | --- |
| [getBase()](#getBase--) | Argument podstawy |
| [getSubscript()](#getSubscript--) | Określa argument subskryptu, który na przykład w przypadku integral ustawia dolną granicę |
| [getSuperscript()](#getSuperscript--) | Określa argument superskryptu, który na przykład w przypadku integral ustawia górną granicę |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Argument podstawy

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement baseArg = naryOperator.getBase();
>  ```

**Zwraca:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```

Określa argument subskryptu, który na przykład w przypadku integral ustawia dolną granicę

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

Określa argument superskryptu, który na przykład w przypadku integral ustawia górną granicę

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**Zwraca:**
[IMathElement](../../com.aspose.slides/imathelement)