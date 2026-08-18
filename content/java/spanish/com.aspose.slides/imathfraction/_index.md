---
title: IMathFraction
second_title: Referencia de API de Aspose.Slides para Java
description: Especifica el objeto fracción compuesto por un numerador y un denominador separados por una barra de fracción.
type: docs
url: /es/com.aspose.slides/imathfraction/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFraction extends IMathElement
```

Especifica el objeto fracción, compuesto por un numerador y un denominador separados por una barra de fracción. La barra de fracción puede ser horizontal o diagonal, según las propiedades de la fracción. El objeto fracción también se utiliza para representar la función de apilamiento, que coloca un elemento sobre otro, sin barra de fracción.

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathFraction mathFraction2 = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```
## Métodos

| Método | Descripción |
| --- | --- |
| [getFractionType()](#getFractionType--) | Tipo de fracción Predeterminado: Bar |
| [setFractionType(int value)](#setFractionType-int-) | Tipo de fracción Predeterminado: Bar |
| [getNumerator()](#getNumerator--) | Numerador |
| [getDenominator()](#getDenominator--) | Denominador |
### getFractionType() {#getFractionType--}
```
public abstract int getFractionType()
```


Tipo de fracción Predeterminado: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**Devuelve:**
int
### setFractionType(int value) {#setFractionType-int-}
```
public abstract void setFractionType(int value)
```


Tipo de fracción Predeterminado: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
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

**Devuelve:**
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

**Devuelve:**
[IMathElement](../../com.aspose.slides/imathelement)