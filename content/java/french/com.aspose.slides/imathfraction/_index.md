---
title: IMathFraction
second_title: "Référence API Aspose.Slides pour Java"
description: "Spécifie l'objet fraction composé d'un numérateur et d'un dénominateur séparés par une barre de fraction."
type: docs
url: /fr/com.aspose.slides/imathfraction/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFraction extends IMathElement
```

Spécifie l'objet fraction, composé d'un numérateur et d'un dénominateur séparés par une barre de fraction. La barre de fraction peut être horizontale ou diagonale, selon les propriétés de la fraction. L'objet fraction est également utilisé pour représenter la fonction empilement, qui place un élément au-dessus d'un autre, sans barre de fraction.

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathFraction mathFraction2 = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFractionType()](#getFractionType--) | Type de fraction Par défaut : Bar |
| [setFractionType(int value)](#setFractionType-int-) | Type de fraction Par défaut : Bar |
| [getNumerator()](#getNumerator--) | Numérateur |
| [getDenominator()](#getDenominator--) | Dénominateur |
### getFractionType() {#getFractionType--}
```
public abstract int getFractionType()
```


Type de fraction Par défaut : Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**Renvoie:**  
int
### setFractionType(int value) {#setFractionType-int-}
```
public abstract void setFractionType(int value)
```


Type de fraction Par défaut : Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getNumerator() {#getNumerator--}
```
public abstract IMathElement getNumerator()
```


Numérateur

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement numerator = mathFraction.getNumerator();
> ```

**Renvoie:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getDenominator() {#getDenominator--}
```
public abstract IMathElement getDenominator()
```


Dénominateur

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement denominator = mathFraction.getDenominator();
> ```

**Renvoie:**  
[IMathElement](../../com.aspose.slides/imathelement)