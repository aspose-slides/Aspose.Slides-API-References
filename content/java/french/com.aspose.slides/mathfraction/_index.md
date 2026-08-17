---
title: MathFraction
second_title: Référence de l'API Aspose.Slides pour Java
description: Spécifie l'objet fraction composé d'un numérateur et d'un dénominateur séparés par une barre de fraction.
type: docs
url: /fr/com.aspose.slides/mathfraction/
---
**Héritage:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Toutes les interfaces implémentées:**
[com.aspose.slides.IMathFraction](../../com.aspose.slides/imathfraction), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathFraction extends MathElementBase implements IMathFraction, IHasControlCharacterProperties
```

Spécifie l’objet fraction, composé d’un numérateur et d’un dénominateur séparés par une barre de fraction. La barre de fraction peut être horizontale ou diagonale, selon les propriétés de la fraction. L’objet fraction est également utilisé pour représenter la fonction de pile, qui place un élément au-dessus d’un autre, sans barre de fraction.

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Initialise MathFraction avec le numérateur, le dénominateur et le type spécifiés |
| [MathFraction(IMathElement numerator, IMathElement denominator)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Initialise un MathFraction de type 'Bar' avec le numérateur et le dénominateur spécifiés |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFractionType()](#getFractionType--) | Type de fraction Par défaut : Bar |
| [setFractionType(int value)](#setFractionType-int-) | Type de fraction Par défaut : Bar |
| [getNumerator()](#getNumerator--) | Numérateur |
| [getDenominator()](#getDenominator--) | Dénominateur |
| [getChildren()](#getChildren--) | Obtenir les éléments enfants |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Propriétés du caractère de contrôle |
### MathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```


 Initialise MathFraction avec le numérateur, le dénominateur et le type spécifiés

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Numérateur |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Dénominateur |
| fractionType | int | Type de fraction |

### MathFraction(IMathElement numerator, IMathElement denominator) {#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathFraction(IMathElement numerator, IMathElement denominator)
```


 Initialise un MathFraction de type 'Bar' avec le numérateur et le dénominateur spécifiés

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"));
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Numérateur |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Dénominateur |

### getFractionType() {#getFractionType--}
```
public final int getFractionType()
```


 Type de fraction Par défaut : Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**Valeur de retour:**
int
### setFractionType(int value) {#setFractionType-int-}
```
public final void setFractionType(int value)
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
public final IMathElement getNumerator()
```


 Numérateur

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement numerator = mathFraction.getNumerator();
> ```

**Valeur de retour:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDenominator() {#getDenominator--}
```
public final IMathElement getDenominator()
```


 Dénominateur

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement denominator = mathFraction.getDenominator();
> ```

**Valeur de retour:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


 Obtenir les éléments enfants

**Valeur de retour:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


 Propriétés du caractère de contrôle

**Valeur de retour:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps