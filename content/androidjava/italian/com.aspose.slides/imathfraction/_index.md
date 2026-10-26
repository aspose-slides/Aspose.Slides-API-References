---
title: IMathFraction
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Specifica l'oggetto frazione composto da un numeratore e un denominatore separati da una barra di frazione.
type: docs
url: /it/com.aspose.slides/imathfraction/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFraction extends IMathElement
```

Specifica l'oggetto frazione, composto da un numeratore e un denominatore separati da una barra di frazione. La barra di frazione può essere orizzontale o diagonale, a seconda delle proprietà della frazione. L'oggetto frazione è anche usato per rappresentare la funzione di impilamento, che posiziona un elemento sopra un altro, senza barra di frazione.

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathFraction mathFraction2 = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFractionType()](#getFractionType--) | Tipo di frazione Predefinito: Bar |
| [setFractionType(int value)](#setFractionType-int-) | Tipo di frazione Predefinito: Bar |
| [getNumerator()](#getNumerator--) | Numeratore |
| [getDenominator()](#getDenominator--) | Denominatore |
### getFractionType() {#getFractionType--}
```
public abstract int getFractionType()
```


Tipo di frazione Predefinito: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**Restituisce:**
int
### setFractionType(int value) {#setFractionType-int-}
```
public abstract void setFractionType(int value)
```


Tipo di frazione Predefinito: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getNumerator() {#getNumerator--}
```
public abstract IMathElement getNumerator()
```


Numeratore

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement numerator = mathFraction.getNumerator();
> ```

**Restituisce:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDenominator() {#getDenominator--}
```
public abstract IMathElement getDenominator()
```


Denominatore

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement denominator = mathFraction.getDenominator();
> ```

**Restituisce:**
[IMathElement](../../com.aspose.slides/imathelement)