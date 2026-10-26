---
title: MathDelimiter
second_title: Aspose.Slides per Android tramite riferimento API Java
description: Specificare l'oggetto delimitatore costituito da caratteri di apertura e chiusura come parentesi, graffe, parentesi quadre e barre verticali, e da uno o più elementi matematici al suo interno separati da un carattere specificato.
type: docs
url: /it/com.aspose.slides/mathdelimiter/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**All Implemented Interfaces:**
[com.aspose.slides.IMathDelimiter](../../com.aspose.slides/imathdelimiter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathDelimiter extends MathElementBase implements IMathDelimiter, IHasControlCharacterProperties
```

Specifica l'oggetto delimitatore, costituito da caratteri di apertura e chiusura (come parentesi, graffe, parentesi quadre e barre verticali), e da uno o più elementi matematici al suo interno, separati da un carattere specificato. Esempi: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

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
| [MathDelimiter(IMathElement element)](#MathDelimiter-com.aspose.slides.IMathElement-) | Inizializza MathDelimiter con l'elemento specificato come unico argomento di base |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getArguments()](#getArguments--) | Uno o più elementi matematici separati da caratteri delimitatori |
| [getBeginningCharacter()](#getBeginningCharacter--) | Delimiter Beginning Character specifica il carattere di inizio, o di apertura, del delimitatore |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Delimiter Beginning Character specifica il carattere di inizio, o di apertura, del delimitatore |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Delimiter Separator Character specifica il carattere che separa gli argomenti nell'oggetto delimitatore |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Delimiter Separator Character specifica il carattere che separa gli argomenti nell'oggetto delimitatore |
| [getEndingCharacter()](#getEndingCharacter--) | Delimiter Ending Character specifica il carattere di fine, o di chiusura, del delimitatore |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Delimiter Ending Character specifica il carattere di fine, o di chiusura, del delimitatore |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Specifica la crescita di BeginningCharacter, SeparatorCharacter, EndingCharacter. Quando è true, i delimitatori crescono verticalmente per corrispondere all'altezza dell'operando |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Specifica la crescita di BeginningCharacter, SeparatorCharacter, EndingCharacter. Quando è true, i delimitatori crescono verticalmente per corrispondere all'altezza dell'operando |
| [getDelimiterShape()](#getDelimiterShape--) | Specifica la forma dei delimitatori nell'oggetto delimitatore |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Specifica la forma dei delimitatori nell'oggetto delimitatore |
| [delimit(char separatorCharacter)](#delimit-char-) | Delimina gli argomenti usando il carattere delimitatore specificato |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Racchiude un elemento matematico nei caratteri specificati, come parentesi o altri caratteri, come cornice |
| [getChildren()](#getChildren--) | Ottiene gli elementi figli |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Proprietà dei caratteri di controllo |
### MathDelimiter(IMathElement element) {#MathDelimiter-com.aspose.slides.IMathElement-}
```
public MathDelimiter(IMathElement element)
```

Inizializza MathDelimiter con l'elemento specificato come unico argomento di base

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
| element | [IMathElement](../../com.aspose.slides/imathelement) | L'elemento base al quale viene applicato il delimitatore. Può essere null. |

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

Delimiter Beginning Character specifica il carattere di inizio, o di apertura, del delimitatore. I delimitatori matematici sono caratteri di incapsulamento come parentesi, parentesi quadre e graffe. Predefinito: '('.

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

Delimiter Beginning Character specifica il carattere di inizio, o di apertura, del delimitatore. I delimitatori matematici sono caratteri di incapsulamento come parentesi, parentesi quadre e graffe. Predefinito: '('.

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

Delimiter Separator Character specifica il carattere che separa gli argomenti nell'oggetto delimitatore. Predefinito: '|'.

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

Delimiter Separator Character specifica il carattere che separa gli argomenti nell'oggetto delimitatore. Predefinito: '|'.

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

Delimiter Ending Character specifica il carattere di fine, o di chiusura, del delimitatore. I delimitatori matematici sono caratteri di incapsulamento come parentesi, parentesi quadre e graffe. Predefinito: ')'.

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

Delimiter Ending Character specifica il carattere di fine, o di chiusura, del delimitatore. I delimitatori matematici sono caratteri di incapsulamento come parentesi, parentesi quadre e graffe. Predefinito: ')'.

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

Specifica la crescita di BeginningCharacter, SeparatorCharacter, EndingCharacter. Quando è true, i delimitatori crescono verticalmente per corrispondere all'altezza dell'operando. Il valore predefinito è true

--------------------

> ```
> Esempio:
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

Specifica la crescita di BeginningCharacter, SeparatorCharacter, EndingCharacter. Quando è true, i delimitatori crescono verticalmente per corrispondere all'altezza dell'operando. Il valore predefinito è true

--------------------

> ```
> Esempio:
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

Specifica la forma dei delimitatori nell'oggetto delimitatore. Quando è MathDelimiterShape.Centered, i delimitatori sono centrati sull'asse matematico del testo matematico e vengono adattati per coprire l'intera altezza del loro contenuto. Quando è MathDelimiterShape.Match, la loro altezza e forma vengono modificate per corrispondere esattamente al contenuto.

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

Specifica la forma dei delimitatori nell'oggetto delimitatore. Quando è MathDelimiterShape.Centered, i delimitatori sono centrati sull'asse matematico del testo matematico e vengono adattati per coprire l'intera altezza del loro contenuto. Quando è MathDelimiterShape.Match, la loro altezza e forma vengono modificate per corrispondere esattamente al contenuto.

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

Delimina gli argomenti usando il carattere delimitatore specificato

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| separatorCharacter | char | carattere delimitatore |

**Restituisce:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Questo oggetto dopo aver applicato il carattere delimitatore
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Racchiude un elemento matematico nei caratteri specificati, come parentesi o altri caratteri, come cornice

--------------------

> ```
> Esempio:
>  
>  IMathDelimiter innerDelimiter = new MathematicalText("x").join(",y").enclose('{', '}');
>  IMathDelimiter outerDelimiter = innerDelimiter.enclose('[', ']');
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| beginningCharacter | char | Carattere di apertura (di solito parentesi sinistra) |
| endingCharacter | char | Carattere di chiusura (di solito parentesi destra) |

**Restituisce:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Se beginningCharacter e endingCharacter sono null, vengono assegnati solo i valori delle proprietà corrispondenti e non viene creato un nuovo oggetto (restituisce questa istanza). Altrimenti, restituisce un nuovo elemento matematico di tipo Delimiter che include i caratteri specificati come cornice e questa istanza di [MathDelimiter](../../com.aspose.slides/mathdelimiter) incorniciata all'interno.
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Ottiene gli elementi figli

**Restituisce:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Proprietà dei caratteri di controllo

**Restituisce:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps