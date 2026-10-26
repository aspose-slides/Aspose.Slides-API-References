---
title: IMathBox
second_title: Riferimento API di Aspose.Slides per Java
description: Specifica l'incapsulamento logico (boxing) di un elemento matematico.
type: docs
url: /it/com.aspose.slides/imathbox/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBox extends IMathElement
```

Specifica l'incapsulamento logico (confezionamento) di un elemento matematico. Per esempio, un oggetto incassato può fungere da emulatore di operatore con o senza un punto di allineamento, fungere da punto di interruzione di riga, o essere raggruppato in modo da non consentire interruzioni di riga al suo interno. Per esempio, l'operatore "==" dovrebbe essere incassato per evitare interruzioni di riga.

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
> ```
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBase()](#getBase--) | Argomento di base |
| [getOperatorEmulator()](#getOperatorEmulator--) | Emulatore di operatore. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Emulatore di operatore. |
| [getNoBreak()](#getNoBreak--) | Nessuna interruzione. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | Nessuna interruzione. |
| [getDifferential()](#getDifferential--) | Differenziale. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Differenziale. |
| [getAlignmentPoint()](#getAlignmentPoint--) | Quando è vero, questo emulatore di operatore funge da punto di allineamento; ossia, i punti di allineamento designati in altre equazioni possono essere allineati con esso. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | Quando è vero, questo emulatore di operatore funge da punto di allineamento; ossia, i punti di allineamento designati in altre equazioni possono essere allineati con esso. |
| [getExplicitBreak()](#getExplicitBreak--) | Interruzione esplicita indica se esiste un'interruzione di riga all'inizio dell'oggetto Box, in modo che la riga vada a capo all'inizio dell'oggetto box. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Interruzione esplicita indica se esiste un'interruzione di riga all'inizio dell'oggetto Box, in modo che la riga vada a capo all'inizio dell'oggetto box. |

### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Argomento di base

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  IMathElement base = box.getBase();
> ```

**Restituisce:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public abstract boolean getOperatorEmulator()
```

Emulatore di operatore. Quando è vero, il box e il suo contenuto si comportano come un unico operatore e ne ereditano le proprietà. Ciò significa, per esempio, che il carattere può fungere da punto di interruzione di riga e può essere allineato ad altri operatori. Gli emulatori di operatore sono spesso usati quando uno o più glifi si combinano per formare un operatore, come '=='. Valore predefinito: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**Restituisce:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public abstract void setOperatorEmulator(boolean value)
```

Emulatore di operatore. Quando è vero, il box e il suo contenuto si comportano come un unico operatore e ne ereditano le proprietà. Ciò significa, per esempio, che il carattere può fungere da punto di interruzione di riga e può essere allineato ad altri operatori. Gli emulatori di operatore sono spesso usati quando uno o più glifi si combinano per formare un operatore, come '=='. Valore predefinito: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public abstract boolean getNoBreak()
```

Nessuna interruzione. Questa proprietà specifica la proprietà "unbreakable" sul box dell'oggetto. Quando è vero, non possono verificarsi interruzioni di riga all'interno del box. Questo può essere importante per gli emulatori di operatore che consistono in più di un operatore binario. Quando questo elemento non è specificato, le interruzioni possono verificarsi all'interno del box. Predefinito: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**Restituisce:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public abstract void setNoBreak(boolean value)
```

Nessuna interruzione. Questa proprietà specifica la proprietà "unbreakable" sul box dell'oggetto. Quando è vero, non possono verificarsi interruzioni di riga all'interno del box. Questo può essere importante per gli emulatori di operatore che consistono in più di un operatore binario. Quando questo elemento non è specificato, le interruzioni possono verificarsi all'interno del box. Predefinito: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public abstract boolean getDifferential()
```

Differenziale. Quando è vero, il box agisce come un differenziale (ad es., \\ud835\\udc51\\ud835\\udc65 in un integrando) e riceve la spaziatura orizzontale appropriata per il differenziale matematico. Valore predefinito: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**Restituisce:**
boolean
### setDifferential(boolean value) {#setDifferential-boolean-}
```
public abstract void setDifferential(boolean value)
```

Differenziale. Quando è vero, il box agisce come un differenziale (ad es., \\ud835\\udc51\\ud835\\udc65 in un integrando) e riceve la spaziatura orizzontale appropriata per il differenziale matematico. Valore predefinito: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getAlignmentPoint() {#getAlignmentPoint--}
```
public abstract boolean getAlignmentPoint()
```

Quando è vero, questo emulatore di operatore funge da punto di allineamento; ossia, i punti di allineamento designati in altre equazioni possono essere allineati con esso. Valore predefinito: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Restituisce:**
boolean
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public abstract void setAlignmentPoint(boolean value)
```

Quando è vero, questo emulatore di operatore funge da punto di allineamento; ossia, i punti di allineamento designati in altre equazioni possono essere allineati con esso. Valore predefinito: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getExplicitBreak() {#getExplicitBreak--}
```
public abstract byte getExplicitBreak()
```

Interruzione esplicita indica se esiste un'interruzione di riga all'inizio dell'oggetto Box, in modo che la riga vada a capo all'inizio dell'oggetto box. Specifica il numero dell'operatore nella riga precedente del testo matematico che deve essere usato come punto di allineamento per la riga corrente del testo matematico. Valori possibili: 1..255 Valore predefinito: 0 (nessuna interruzione esplicita)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Restituisce:**
byte
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public abstract void setExplicitBreak(byte value)
```

Interruzione esplicita indica se esiste un'interruzione di riga all'inizio dell'oggetto Box, in modo che la riga vada a capo all'inizio dell'oggetto box. Specifica il numero dell'operatore nella riga precedente del testo matematico che deve essere usato come punto di allineamento per la riga corrente del testo matematico. Valori possibili: 1..255 Valore predefinito: 0 (nessuna interruzione esplicita)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |