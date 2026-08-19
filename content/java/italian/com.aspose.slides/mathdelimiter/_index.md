---
title: MathDelimiter
second_title: Riferimento API di Aspose.Slides per Java
description: Specifica l'oggetto delimitatore composto da caratteri di apertura e chiusura come parentesi tonde, graffe, parentesi quadre e barre verticali e da uno o più elementi matematici al suo interno separati da un carattere specificato.
type: docs
url: /it/com.aspose.slides/mathdelimiter/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Tutte le interfacce implementate:**
[com.aspose.slides.IMathDelimiter](../../com.aspose.slides/imathdelimiter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathDelimiter extends MathElementBase implements IMathDelimiter, IHasControlCharacterProperties
```

Specifica l'oggetto delimitatore, composto da caratteri di apertura e chiusura (come parentesi tonde, graffe, parentesi quadre e barre verticali), e uno o più elementi matematici al suo interno, separati da un carattere specificato. Esempi: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MathDelimiter(IMathElement element)](#MathDelimiter-com.aspose.slides.IMathElement-) | Inizializza MathDelimiter con l'elemento specificato come argomento base singolo |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getArguments()](#getArguments--) | Uno o più elementi matematici separati da caratteri delimitatori |
| [getBeginningCharacter()](#getBeginningCharacter--) | Il carattere di inizio delimitatore specifica il carattere delimitatore di apertura. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Il carattere di inizio delimitatore specifica il carattere delimitatore di apertura. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Il carattere separatore del delimitatore specifica il carattere che separa gli argomenti nell'oggetto delimitatore. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Il carattere separatore del delimitatore specifica il carattere che separa gli argomenti nell'oggetto delimitatore. |
| [getEndingCharacter()](#getEndingCharacter--) | Il carattere di fine delimitatore specifica il carattere delimitatore di chiusura. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Il carattere di fine delimitatore specifica il carattere delimitatore di chiusura. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Specifica la crescita di BeginningCharacter, SeparatorCharacter, EndingCharacter. Quando vero, i delimitatori crescono verticalmente per corrispondere all'altezza dell'operando. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Specifica la crescita di BeginningCharacter, SeparatorCharacter, EndingCharacter. Quando vero, i delimitatori crescono verticalmente per corrispondere all'altezza dell'operando. |
| [getDelimiterShape()](#getDelimiterShape--) | Specifica la forma dei delimitatori nell'oggetto delimitatore. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Specifica la forma dei delimitatori nell'oggetto delimitatore. |
| [delimit(char separatorCharacter)](#delimit-char-) | Delimita gli argomenti usando il carattere delimitatore specificato |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Racchiude un elemento matematico nei caratteri specificati, come parentesi o altri caratteri, come cornice |
| [getChildren()](#getChildren--) | Ottieni elementi figli |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Proprietà dei caratteri di controllo |
### MathDelimiter(IMathElement element) {#MathDelimiter-com.aspose.slides.IMathElement-}
```
public MathDelimiter(IMathElement element)
```

Inizializza MathDelimiter con l'elemento specificato come argomento base singolo

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | L'elemento base a cui viene applicato il delimitatore. Può essere null. |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```

Uno o più elementi matematici separati da caratteri delimitatori

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  IMathElementCollection arguments = delimiter.getArguments();
> ```


**Restituisce:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBeginningCharacter() {#getBeginningCharacter--}
```
public final char getBeginningCharacter()
```

Il carattere di inizio delimitatore specifica il carattere delimitatore di apertura. I delimitatori matematici sono caratteri di incapsulamento come parentesi tonde, parentesi quadre e graffe. Il valore predefinito: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Restituisce:**
char
### setBeginningCharacter(char value) {#setBeginningCharacter-char-}
```
public final void setBeginningCharacter(char value)
```

Il carattere di inizio delimitatore specifica il carattere delimitatore di apertura. I delimitatori matematici sono caratteri di incapsulamento come parentesi tonde, parentesi quadre e graffe. Il valore predefinito: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | char |  |

### getSeparatorCharacter() {#getSeparatorCharacter--}
```
public final char getSeparatorCharacter()
```

Il carattere separatore del delimitatore specifica il carattere che separa gli argomenti nell'oggetto delimitatore. Il valore predefinito: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Restituisce:**
char
### setSeparatorCharacter(char value) {#setSeparatorCharacter-char-}
```
public final void setSeparatorCharacter(char value)
```

Il carattere separatore del delimitatore specifica il carattere che separa gli argomenti nell'oggetto delimitatore. Il valore predefinito: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | char |  |

### getEndingCharacter() {#getEndingCharacter--}
```
public final char getEndingCharacter()
```

Il carattere di fine delimitatore specifica il carattere delimitatore di chiusura. I delimitatori matematici sono caratteri di incapsulamento come parentesi tonde, parentesi quadre e graffe. Il valore predefinito: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Restituisce:**
char
### setEndingCharacter(char value) {#setEndingCharacter-char-}
```
public final void setEndingCharacter(char value)
```

Il carattere di fine delimitatore specifica il carattere delimitatore di chiusura. I delimitatori matematici sono caratteri di incapsulamento come parentesi tonde, parentesi quadre e graffe. Il valore predefinito: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | char |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public final boolean getGrowToMatchOperandHeight()
```

Specifica la crescita di BeginningCharacter, SeparatorCharacter, EndingCharacter. Quando vero, i delimitatori crescono verticalmente per corrispondere all'altezza dell'operando. Il valore predefinito è true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Restituisce:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```

Specifica la crescita di BeginningCharacter, SeparatorCharacter, EndingCharacter. Quando vero, i delimitatori crescono verticalmente per corrispondere all'altezza dell'operando. Il valore predefinito è true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getDelimiterShape() {#getDelimiterShape--}
```
public final int getDelimiterShape()
```

Specifica la forma dei delimitatori nell'oggetto delimitatore. Quando è MathDelimiterShape.Centered, i delimitatori sono centrati attorno all'asse matematico del testo matematico e sono comunque adattati per coprire l'intera altezza del loro contenuto. Quando è MathDelimiterShape.Match, la loro altezza e forma sono modificate per corrispondere esattamente al contenuto.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Restituisce:**
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public final void setDelimiterShape(int value)
```

Specifica la forma dei delimitatori nell'oggetto delimitatore. Quando è MathDelimiterShape.Centered, i delimitatori sono centrati attorno all'asse matematico del testo matematico e sono comunque adattati per coprire l'intera altezza del loro contenuto. Quando è MathDelimiterShape.Match, la loro altezza e forma sono modificate per corrispondere esattamente al contenuto.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

Delimita gli argomenti usando il carattere delimitatore specificato

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| separatorCharacter | char | carattere delimitatore |

**Restituisce:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Questo oggetto dopo l'applicazione del carattere delimitatore
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Racchiude un elemento matematico nei caratteri specificati, come parentesi o altri caratteri, come cornice

--------------------

> ```
> Example:
>  
>  IMathDelimiter innerDelimiter = new MathematicalText("x").join(",y").enclose('{', '}');
>  IMathDelimiter outerDelimiter = innerDelimiter.enclose('[', ']');
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| beginningCharacter | char | Carattere di inizio (di solito parentesi sinistra) |
| endingCharacter | char | Carattere di fine (di solito parentesi destra) |

**Restituisce:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Se beginningCharacter e endingCharacter sono null, le proprietà corrispondenti ricevono solo valori e non viene creato un nuovo oggetto (restituisce questa istanza). Altrimenti, restituisce un nuovo elemento matematico di tipo Delimiter che include i caratteri specificati come cornice e questa istanza di [MathDelimiter](../../com.aspose.slides/mathdelimiter) incorniciata al suo interno.
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Ottieni elementi figli

**Restituisce:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Proprietà dei caratteri di controllo

**Restituisce:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps