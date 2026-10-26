---
title: IMathDelimiter
second_title: Riferimento API di Aspose.Slides per Java
description: Specifica l'oggetto delimitatore costituito da caratteri di apertura e chiusura come parentesi, graffe, parentesi quadre e barre verticali e da uno o più elementi matematici all'interno separati da un carattere specificato.
type: docs
url: /it/com.aspose.slides/imathdelimiter/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathDelimiter extends IMathElement
```

Specifica l'oggetto delimitatore, costituito da caratteri di apertura e chiusura (come parentesi tonde, graffe, quadre e barre verticali), e da uno o più elementi matematici all'interno, separati da un carattere specificato. Esempi: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```
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
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Specifica la crescita di BeginningCharacter, SeparatorCharacter, EndingCharacter. Quando vero, i delimitatori crescono verticalmente per corrispondere all'altezza del loro operando. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Specifica la crescita di BeginningCharacter, SeparatorCharacter, EndingCharacter. Quando vero, i delimitatori crescono verticalmente per corrispondere all'altezza del loro operando. |
| [getDelimiterShape()](#getDelimiterShape--) | Specifica la forma dei delimitatori nell'oggetto delimitatore. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Specifica la forma dei delimitatori nell'oggetto delimitatore. |
| [delimit(char separatorCharacter)](#delimit-char-) | Delimita gli argomenti usando il carattere delimitatore specificato |
### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
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
public abstract char getBeginningCharacter()
```

Il carattere di inizio delimitatore specifica il carattere delimitatore di apertura. I delimitatori matematici sono caratteri di chiusura come parentesi tonde, quadre e graffe. Il valore predefinito: '('.

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
public abstract void setBeginningCharacter(char value)
```

Il carattere di inizio delimitatore specifica il carattere delimitatore di apertura. I delimitatori matematici sono caratteri di chiusura come parentesi tonde, quadre e graffe. Il valore predefinito: '('.

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
public abstract char getSeparatorCharacter()
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
public abstract void setSeparatorCharacter(char value)
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
public abstract char getEndingCharacter()
```

Il carattere di fine delimitatore specifica il carattere delimitatore di chiusura. I delimitatori matematici sono caratteri di chiusura come parentesi tonde, quadre e graffe. Il valore predefinito: ')'.

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
public abstract void setEndingCharacter(char value)
```

Il carattere di fine delimitatore specifica il carattere delimitatore di chiusura. I delimitatori matematici sono caratteri di chiusura come parentesi tonde, quadre e graffe. Il valore predefinito: ')'.

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
public abstract boolean getGrowToMatchOperandHeight()
```

Specifică la crescita di BeginningCharacter, SeparatorCharacter, EndingCharacter. Quando vero, i delimitatori crescono verticalmente per corrispondere all'altezza del loro operando. Il valore predefinito è vero

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
public abstract void setGrowToMatchOperandHeight(boolean value)
```

Specifică la crescita di BeginningCharacter, SeparatorCharacter, EndingCharacter. Quando vero, i delimitatori crescono verticalmente per corrispondere all'altezza del loro operando. Il valore predefinito è vero

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
public abstract int getDelimiterShape()
```

Specifică la forma dei delimitatori nell'oggetto delimitatore. Quando è MathDelimiterShape.Centered, i delimitatori sono centrati sull'asse matematico del testo matematico e possono comunque adattarsi all'intera altezza del loro contenuto. Quando è MathDelimiterShape.Match, la loro altezza e forma vengono modificate per corrispondere esattamente al loro contenuto.

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
public abstract void setDelimiterShape(int value)
```

Specifică la forma dei delimitatori nell'oggetto delimitatore. Quando è MathDelimiterShape.Centered, i delimitatori sono centrati sull'asse matematico del testo matematico e possono comunque adattarsi all'intera altezza del loro contenuto. Quando è MathDelimiterShape.Match, la loro altezza e forma vengono modificate per corrispondere esattamente al loro contenuto.

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
public abstract IMathDelimiter delimit(char separatorCharacter)
```

Delimita gli argomenti usando il carattere delimitatore specificato

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.delimit('|');
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| separatorCharacter | char | carattere delimitatore |

**Restituisce:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Questo oggetto dopo aver applicato il carattere delimitatore