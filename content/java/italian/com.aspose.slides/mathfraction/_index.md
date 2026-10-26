---
title: MathFraction
second_title: Riferimento API Aspose.Slides per Java
description: Specifica l'oggetto frazione composto da un numeratore e un denominatore separati da una barra della frazione.
type: docs
url: /it/com.aspose.slides/mathfraction/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Tutte le interfacce implementate:**
[com.aspose.slides.IMathFraction](../../com.aspose.slides/imathfraction), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathFraction extends MathElementBase implements IMathFraction, IHasControlCharacterProperties
```

Specifica l'oggetto frazione, composto da un numeratore e un denominatore separati da una barra frazione. La barra può essere orizzontale o diagonale, a seconda delle proprietà della frazione. L'oggetto frazione è anche usato per rappresentare la funzione stack, che posiziona un elemento sopra un altro, senza barra frazione.

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Initializes MathFraction with the specified numerator, denominator and type |
| [MathFraction(IMathElement numerator, IMathElement denominator)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Initializes a MathFraction of type 'Bar' with the specified numerator and denominator |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFractionType()](#getFractionType--) | Tipo di frazione Predefinito: Bar |
| [setFractionType(int value)](#setFractionType-int-) | Tipo di frazione Predefinito: Bar |
| [getNumerator()](#getNumerator--) | Numeratore |
| [getDenominator()](#getDenominator--) | Denominatore |
| [getChildren()](#getChildren--) | Ottieni gli elementi figli |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Proprietà del carattere di controllo |
### MathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```


Inizializza MathFraction con il numeratore, il denominatore e il tipo specificati

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Numeratore |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Denominatore |
| fractionType | int | Tipo di frazione |

### MathFraction(IMathElement numerator, IMathElement denominator) {#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathFraction(IMathElement numerator, IMathElement denominator)
```


Inizializza un MathFraction di tipo 'Bar' con il numeratore e il denominatore specificati

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"));
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Numeratore |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Denominatore |

### getFractionType() {#getFractionType--}
```
public final int getFractionType()
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
public final void setFractionType(int value)
```


Tipo di frazione Predefinito: Bar

--------------------

> ```
> Esempio:
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
public final IMathElement getNumerator()
```


Numeratore

--------------------

> ```
> Esempio:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement numerator = mathFraction.getNumerator();
> ```

**Restituisce:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDenominator() {#getDenominator--}
```
public final IMathElement getDenominator()
```


Denominatore

--------------------

> ```
> Esempio:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement denominator = mathFraction.getDenominator();
> ```

**Restituisce:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Ottieni gli elementi figli

**Restituisce:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Proprietà del carattere di controllo

**Restituisce:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps