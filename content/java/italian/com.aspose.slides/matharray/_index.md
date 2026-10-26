---
title: MathArray
second_title: Riferimento API di Aspose.Slides per Java
description: Specifica un array verticale di equazioni o di qualsiasi oggetto matematico
type: docs
url: /it/com.aspose.slides/matharray/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Tutte le Interfacce Implementate:**
[com.aspose.slides.IMathArray](../../com.aspose.slides/imatharray)
```
public final class MathArray extends MathElementBase implements IMathArray
```

Specifica un array verticale di equazioni o di qualsiasi oggetto matematico

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MathArray(IMathElement element)](#MathArray-com.aspose.slides.IMathElement-) | Crea un array matematico e inserisce l'elemento specificato in esso |
| [MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)](#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | Crea un array matematico e inserisce gli elementi specificati in esso |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getArguments()](#getArguments--) | Il set di elementi dell'array |
| [getBaseJustification()](#getBaseJustification--) | Specifica l'allineamento dell'array rispetto al testo circostante. Il testo fuori dall'array può essere allineato con il bordo inferiore, superiore o al centro di un oggetto array. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Specifica l'allineamento dell'array rispetto al testo circostante. Il testo fuori dall'array può essere allineato con il bordo inferiore, superiore o al centro di un oggetto array. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Distribuzione Massima Quando true, l'array è spaziato alla larghezza massima dell'elemento contenitore (pagina, colonna, cella, ecc.). |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Distribuzione Massima Quando true, l'array è spaziato alla larghezza massima dell'elemento contenitore (pagina, colonna, cella, ecc.). |
| [getObjectDistribution()](#getObjectDistribution--) | Distribuzione dell'Oggetto Quando true, il contenuto dell'array è spaziato alla larghezza massima dell'oggetto array. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Distribuzione dell'Oggetto Quando true, il contenuto dell'array è spaziato alla larghezza massima dell'oggetto array. |
| [getRowSpacingRule()](#getRowSpacingRule--) | Il tipo di spaziatura verticale tra gli elementi dell'array. Valore predefinito: SingleLineGap |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | Il tipo di spaziatura verticale tra gli elementi dell'array. Valore predefinito: SingleLineGap |
| [getRowSpacing()](#getRowSpacing--) | Spaziatura tra le righe di un array. Viene usata solo quando RowSpacingRule è impostato a 3 Exactly, nel qual caso l'unità di misura è punti, oppure Multiple, nel qual caso l'unità è mezze righe. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Spaziatura tra le righe di un array. Viene usata solo quando RowSpacingRule è impostato a 3 Exactly, nel qual caso l'unità di misura è punti, oppure Multiple, nel qual caso l'unità è mezze righe. |
| [getChildren()](#getChildren--) | Ottieni gli elementi figli |
### MathArray(IMathElement element) {#MathArray-com.aspose.slides.IMathElement-}
```
public MathArray(IMathElement element)
```


Crea un array matematico e inserisce l'elemento specificato in esso

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | L'elemento da inserire nell'array |

### MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements) {#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)
```


Crea un array matematico e inserisce gli elementi specificati in esso

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| elements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | Gli elementi da inserire nell'array |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```


Il set di elementi dell'array

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
> ```

**Restituisce:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```


Specifică l'allineamento dell'array rispetto al testo circostante. Il testo fuori dall'array può essere allineato con il bordo inferiore, superiore o al centro di un oggetto array. Valore predefinito: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Restituisce:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```


Specifică l'allineamento dell'array rispetto al testo circostante. Il testo fuori dall'array può essere allineato con il bordo inferiore, superiore o al centro di un oggetto array. Valore predefinito: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getMaximumDistribution() {#getMaximumDistribution--}
```
public final boolean getMaximumDistribution()
```


Distribuzione Massima Quando true, l'array è spaziato alla larghezza massima dell'elemento contenitore (pagina, colonna, cella, ecc.).

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Restituisce:**
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public final void setMaximumDistribution(boolean value)
```


Distribuzione Massima Quando true, l'array è spaziato alla larghezza massima dell'elemento contenitore (pagina, colonna, cella, ecc.).

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getObjectDistribution() {#getObjectDistribution--}
```
public final boolean getObjectDistribution()
```


Distribuzione dell'Oggetto Quando true, il contenuto dell'array è spaziato alla larghezza massima dell'oggetto array.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Restituisce:**
boolean
### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public final void setObjectDistribution(boolean value)
```


Distribuzione dell'Oggetto Quando true, il contenuto dell'array è spaziato alla larghezza massima dell'oggetto array.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getRowSpacingRule() {#getRowSpacingRule--}
```
public final int getRowSpacingRule()
```


Il tipo di spaziatura verticale tra gli elementi dell'array. Valore predefinito: SingleLineGap

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Restituisce:**
int
### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public final void setRowSpacingRule(int value)
```


Il tipo di spaziatura verticale tra gli elementi dell'array. Valore predefinito: SingleLineGap

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getRowSpacing() {#getRowSpacing--}
```
public final long getRowSpacing()
```


Spaziatura tra le righe di un array. Viene usata solo quando RowSpacingRule è impostato a 3 Exactly, nel qual caso l'unità di misura è punti, oppure Multiple, nel qual caso l'unità è mezze righe. Valore predefinito: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Restituisce:**
long
### setRowSpacing(long value) {#setRowSpacing-long-}
```
public final void setRowSpacing(long value)
```


Spaziatura tra le righe di un array. Viene usata solo quando RowSpacingRule è impostato a 3 Exactly, nel qual caso l'unità di misura è punti, oppure Multiple, nel qual caso l'unità è mezze righe. Valore predefinito: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | long |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Ottieni gli elementi figli

**Restituisce:**
com.aspose.slides.IMathElement[]