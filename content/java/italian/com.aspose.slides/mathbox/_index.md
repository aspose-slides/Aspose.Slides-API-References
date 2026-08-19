---
title: MathBox
second_title: Riferimento API Aspose.Slides per Java
description: Specifica l'incapsulamento logico (pacchettizzazione) dell'elemento matematico.
type: docs
url: /it/com.aspose.slides/mathbox/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Tutte le interfacce implementate:**
[com.aspose.slides.IMathBox](../../com.aspose.slides/imathbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBox extends MathElementBase implements IMathBox, IHasControlCharacterProperties
```

Specifica l'incapsulamento logico (pacchettizzazione) dell'elemento matematico. Ad esempio, un oggetto incapsulato può fungere da emulatore di operatore con o senza un punto di allineamento, fungere da punto di interruzione di riga, o essere raggruppato in modo da non consentire interruzioni di linea al suo interno. Per esempio, l'operatore "==" dovrebbe essere incapsulato per prevenire interruzioni di linea.

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MathBox(IMathElement element)](#MathBox-com.aspose.slides.IMathElement-) | Inizializza MathBox con l'elemento specificato come argomento |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBase()](#getBase--) | Argomento base |
| [getOperatorEmulator()](#getOperatorEmulator--) | Emulatore di Operatore. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Emulatore di Operatore. |
| [getNoBreak()](#getNoBreak--) | Nessuna interruzione Questa proprietà specifica la proprietà "unbreakable" sull'oggetto box. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | Nessuna interruzione Questa proprietà specifica la proprietà "unbreakable" sull'oggetto box. |
| [getDifferential()](#getDifferential--) | Differenziale Quando vero, la scatola agisce come un differenziale (ad esempio, \\ud835\\udc51\\ud835\\udc65 in un integrando), e riceve lo spaziamento orizzontale appropriato per il differenziale matematico. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Differenziale Quando vero, la scatola agisce come un differenziale (ad esempio, \\ud835\\udc51\\ud835\\udc65 in un integrando), e riceve lo spaziamento orizzontale appropriato per il differenziale matematico. |
| [getAlignmentPoint()](#getAlignmentPoint--) | Quando vero, questo emulatore di operatore funge da punto di allineamento; cioè, i punti di allineamento designati in altre equazioni possono essere allineati con esso. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | Quando vero, questo emulatore di operatore funge da punto di allineamento; cioè, i punti di allineamento designati in altre equazioni possono essere allineati con esso. |
| [getExplicitBreak()](#getExplicitBreak--) | Interruzione esplicita specifica se vi è un'interruzione di riga all'inizio dell'oggetto Box, in modo che la linea si avvolga all'inizio dell'oggetto box. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Interruzione esplicita specifica se vi è un'interruzione di riga all'inizio dell'oggetto Box, in modo che la linea si avvolga all'inizio dell'oggetto box. |
| [getChildren()](#getChildren--) | Ottiene gli elementi figli |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Proprietà dei Caratteri di Controllo |
### MathBox(IMathElement element) {#MathBox-com.aspose.slides.IMathElement-}
```
public MathBox(IMathElement element)
```

Inizializza MathBox con l'elemento specificato come argomento

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | L'elemento base a cui viene applicata la scatola. Può essere null. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Argomento base

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  IMathElement base = box.getBase();
> ```

**Restituisce:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public final boolean getOperatorEmulator()
```

Emulatore di Operatore. Quando vero, la scatola e i suoi contenuti si comportano come un singolo operatore e ne ereditano le proprietà. Ciò significa, per esempio, che il carattere può fungere da punto per un'interruzione di riga e può essere allineato ad altri operatori. Gli emulatori di operatore sono spesso usati quando uno o più glifi si combinano per formare un operatore, come '=='. Valore predefinito: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**Restituisce:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public final void setOperatorEmulator(boolean value)
```

Emulatore di Operatore. Quando vero, la scatola e i suoi contenuti si comportano come un singolo operatore e ne ereditano le proprietà. Ciò significa, per esempio, che il carattere può fungere da punto per un'interruzione di riga e può essere allineato ad altri operatori. Gli emulatori di operatore sono spesso usati quando uno o più glifi si combinano per formare un operatore, come '=='. Valore predefinito: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public final boolean getNoBreak()
```

Nessuna interruzione Questa proprietà specifica la proprietà "unbreakable" sull'oggetto box. Quando vero, nessuna interruzione di riga può verificarsi all'interno della scatola. Questo può essere importante per gli emulatori di operatore che consistono in più di un operatore binario. Quando questo elemento non è specificato, le interruzioni possono verificarsi all'interno della scatola. Predefinito: true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**Restituisce:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public final void setNoBreak(boolean value)
```

Nessuna interruzione Questa proprietà specifica la proprietà "unbreakable" sull'oggetto box. Quando vero, nessuna interruzione di riga può verificarsi all'interno della scatola. Questo può essere importante per gli emulatori di operatore che consistono in più di un operatore binario. Quando questo elemento non è specificato, le interruzioni possono verificarsi all'interno della scatola. Predefinito: true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public final boolean getDifferential()
```

Differenziale Quando vero, la scatola agisce come un differenziale (ad esempio, \\ud835\\udc51\\ud835\\udc65 in un integrando), e riceve lo spaziamento orizzontale appropriato per il differenziale matematico. Predefinito: false

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
public final void setDifferential(boolean value)
```

Differenziale Quando vero, la scatola agisce come un differenziale (ad esempio, \\ud835\\udc51\\ud835\\udc65 in un integrando), e riceve lo spaziamento orizzontale appropriato per il differenziale matematico. Predefinito: false

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
public final boolean getAlignmentPoint()
```

Quando vero, questo emulatore di operatore funge da punto di allineamento; cioè, i punti di allineamento designati in altre equazioni possono essere allineati con esso. Predefinito: false

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
public final void setAlignmentPoint(boolean value)
```

Quando vero, questo emulatore di operatore funge da punto di allineamento; cioè, i punti di allineamento designati in altre equazioni possono essere allineati con esso. Predefinito: false

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
public final byte getExplicitBreak()
```

Interruzione esplicita specifica se vi è un'interruzione di riga all'inizio dell'oggetto Box, in modo che la linea si avvolga all'inizio dell'oggetto box. Specifica il numero dell'operatore sulla riga precedente del testo matematico che deve essere usato come punto di allineamento per la riga corrente del testo matematico valori possibili: 1..255 Predefinito: 0 (nessuna interruzione esplicita)

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
public final void setExplicitBreak(byte value)
```

Interruzione esplicita specifica se vi è un'interruzione di riga all'inizio dell'oggetto Box, in modo che la linea si avvolga all'inizio dell'oggetto box. Specifica il numero dell'operatore sulla riga precedente del testo matematico che deve essere usato come punto di allineamento per la riga corrente del testo matematico valori possibili: 1..255 Predefinito: 0 (nessuna interruzione esplicita)

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

Proprietà dei Caratteri di Controllo

**Restituisce:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps