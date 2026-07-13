---
title: MathNaryOperator
second_title: Aspose.Slides per Android via Java API Reference
description: Specifica un oggetto matematico N-ario come Somma e Integrale.
type: docs
url: /it/com.aspose.slides/mathnaryoperator/
---
**Ereditarietà:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Tutte le interfacce implementate:**
[com.aspose.slides.IMathNaryOperator](../../com.aspose.slides/imathnaryoperator), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathNaryOperator extends MathElementBase implements IMathNaryOperator, IHasControlCharacterProperties
```

Specifica un oggetto matematico N-ario, come Somma e Integrale. È composto da un operatore, una base (o operando) e limiti superiori e inferiori opzionali. Esempi di operatori N-ari sono: Somma, Unione, Intersezione, Integrale

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Inizializza una nuova istanza della classe MathNaryOperator. |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Inizializza una nuova istanza della classe MathNaryOperator. |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#MathNaryOperator-char-com.aspose.slides.IMathElement-) | Inizializza una nuova istanza della classe MathNaryOperator. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBase()](#getBase--) | Argomento base |
| [getSubscript()](#getSubscript--) | Specifica un argomento di pedice che, ad esempio, nel caso di un integrale, imposta il limite inferiore |
| [getSuperscript()](#getSuperscript--) | Specifica un argomento di apice che, ad esempio, nel caso di un integrale, imposta il limite superiore |
| [getOperator()](#getOperator--) | Carattere dell'operatore N-ario per esempio: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | Carattere dell'operatore N-ario per esempio: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | La posizione dei limiti (pedice e apice) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | La posizione dei limiti (pedice e apice) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Il carattere dell'operatore cresce verticalmente per corrispondere all'altezza del suo operando |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Il carattere dell'operatore cresce verticalmente per corrispondere all'altezza del suo operando |
| [getHideSubscript()](#getHideSubscript--) | Nascondi pedice |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | Nascondi pedice |
| [getHideSuperscript()](#getHideSuperscript--) | Nascondi apice |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | Nascondi apice |
| [getChildren()](#getChildren--) | Ottieni gli elementi figli |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Proprietà del carattere di controllo |
### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```

Inizializza una nuova istanza della classe MathNaryOperator.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i=0"), new MathematicalText("\ud835\udc5b"));
```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| operatorSymbol | char | Simbolo dell'operatore N-ario |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argomento base |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Limite inferiore |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Limite superiore |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```

Inizializza una nuova istanza della classe MathNaryOperator.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i"));
```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| operatorSymbol | char | Simbolo dell'operatore N-ario |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argomento base |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Limite inferiore |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#MathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```

Inizializza una nuova istanza della classe MathNaryOperator.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"));
```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| operatorSymbol | char | Simbolo dell'operatore N-ario |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argomento base |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Argomento base

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement baseArg = naryOperator.getBase();
> ```

**Restituisce:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```

Specifică un argomento di pedice che, ad esempio, nel caso di un integrale, imposta il limite inferiore

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
> ```

**Restituisce:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```

Specifică un argomento di apice che, ad esempio, nel caso di un integrale, imposta il limite superiore

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**Restituisce:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperator() {#getOperator--}
```
public final char getOperator()
```

Carattere dell'operatore N-ario per esempio: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Restituisce:**
char
### setOperator(char value) {#setOperator-char-}
```
public final void setOperator(char value)
```

Carattere dell'operatore N-ario per esempio: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | char |  |

### getLimitLocation() {#getLimitLocation--}
```
public final int getLimitLocation()
```

La posizione dei limiti (pedice e apice)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Restituisce:**
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public final void setLimitLocation(int value)
```

La posizione dei limiti (pedice e apice)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public final boolean getGrowToMatchOperandHeight()
```

Il carattere dell'operatore cresce verticalmente per corrispondere all'altezza del suo operando

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Restituisce:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```

Il carattere dell'operatore cresce verticalmente per corrispondere all'altezza del suo operando

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getHideSubscript() {#getHideSubscript--}
```
public final boolean getHideSubscript()
```

Nascondi pedice

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Restituisce:**
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public final void setHideSubscript(boolean value)
```

Nascondi pedice

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getHideSuperscript() {#getHideSuperscript--}
```
public final boolean getHideSuperscript()
```

Nascondi apice

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Restituisce:**
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public final void setHideSuperscript(boolean value)
```

Nascondi apice

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

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