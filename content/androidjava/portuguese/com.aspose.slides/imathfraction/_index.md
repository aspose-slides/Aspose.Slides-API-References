---
title: IMathFraction
second_title: Aspose.Slides para Android via Referência da API Java
description: Especifica o objeto fração composto por um numerador e um denominador separados por uma barra de fração.
type: docs
url: /pt/com.aspose.slides/imathfraction/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFraction extends IMathElement
```

Especifica o objeto fração, composto por um numerador e um denominador separados por uma barra de fração. A barra de fração pode ser horizontal ou diagonal, dependendo das propriedades da fração. O objeto fração também é usado para representar a função de empilhamento, que coloca um elemento acima de outro, sem barra de fração.

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathFraction mathFraction2 = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```
## Métodos

| Método | Descrição |
| --- | --- |
| [getFractionType()](#getFractionType--) | Tipo de fração Default: Bar |
| [setFractionType(int value)](#setFractionType-int-) | Tipo de fração Default: Bar |
| [getNumerator()](#getNumerator--) | Numerador |
| [getDenominator()](#getDenominator--) | Denominador |
### getFractionType() {#getFractionType--}
```
public abstract int getFractionType()
```


Tipo de fração Default: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**Retorna:**
int
### setFractionType(int value) {#setFractionType-int-}
```
public abstract void setFractionType(int value)
```


Tipo de fração Default: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getNumerator() {#getNumerator--}
```
public abstract IMathElement getNumerator()
```


Numerador

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement numerator = mathFraction.getNumerator();
> ```

**Retorna:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDenominator() {#getDenominator--}
```
public abstract IMathElement getDenominator()
```


Denominador

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement denominator = mathFraction.getDenominator();
> ```

**Retorna:**
[IMathElement](../../com.aspose.slides/imathelement)