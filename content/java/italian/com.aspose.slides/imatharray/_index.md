---
title: IMathArray
second_title: Riferimento API di Aspose.Slides per Java
description: Specifica un array verticale di equazioni o di qualsiasi oggetto matematico
type: docs
url: /it/com.aspose.slides/imatharray/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathArray extends IMathElement
```

Specifica un array verticale di equazioni o di qualsiasi oggetto matematico

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getArguments()](#getArguments--) | L'insieme degli elementi dell'array |
| [getBaseJustification()](#getBaseJustification--) | Specifica l'allineamento dell'array rispetto al testo circostante. Il testo esterno all'array può essere allineato con il fondo, la parte superiore o il centro di un oggetto array. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Specifica l'allineamento dell'array rispetto al testo circostante. Il testo esterno all'array può essere allineato con il fondo, la parte superiore o il centro di un oggetto array. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Distribuzione massima. Quando è true, l'array è spaziato alla larghezza massima dell'elemento contenitore (pagina, colonna, cella, ecc.). |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Distribuzione massima. Quando è true, l'array è spaziato alla larghezza massima dell'elemento contenitore (pagina, colonna, cella, ecc.). |
| [getObjectDistribution()](#getObjectDistribution--) | Distribuzione dell'oggetto. Quando è true, il contenuto dell'array è spaziato alla larghezza massima dell'oggetto array. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Distribuzione dell'oggetto. Quando è true, il contenuto dell'array è spaziato alla larghezza massima dell'oggetto array. |
| [getRowSpacingRule()](#getRowSpacingRule--) | Il tipo di spaziatura verticale tra gli elementi dell'array |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | Il tipo di spaziatura verticale tra gli elementi dell'array |
| [getRowSpacing()](#getRowSpacing--) | Spaziatura tra le righe di un array. È usata solo quando RowSpacingRule è impostato a 3 Exactly, nel qual caso l'unità di misura è punti, o Multiple, nel qual caso l'unità di misura è mezze linee. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Spaziatura tra le righe di un array. È usata solo quando RowSpacingRule è impostato a 3 Exactly, nel qual caso l'unità di misura è punti, o Multiple, nel qual caso l'unità di misura è mezze linee. |

### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

L'insieme degli elementi dell'array

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
public abstract int getBaseJustification()
```

Specifica l'allineamento dell'array rispetto al testo circostante. Il testo esterno all'array può essere allineato con il fondo, la parte superiore o il centro di un oggetto array. Valore predefinito: Center

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
public abstract void setBaseJustification(int value)
```

Specifica l'allineamento dell'array rispetto al testo circostante. Il testo esterno all'array può essere allineato con il fondo, la parte superiore o il centro di un oggetto array. Valore predefinito: Center

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
public abstract boolean getMaximumDistribution()
```

Distribuzione massima. Quando è true, l'array è spaziato alla larghezza massima dell'elemento contenitore (pagina, colonna, cella, ecc.).

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
public abstract void setMaximumDistribution(boolean value)
```

Distribuzione massima. Quando è true, l'array è spaziato alla larghezza massima dell'elemento contenitore (pagina, colonna, cella, ecc.).

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
public abstract boolean getObjectDistribution()
```

Distribuzione dell'oggetto. Quando è true, il contenuto dell'array è spaziato alla larghezza massima dell'oggetto array.

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
public abstract void setObjectDistribution(boolean value)
```

Distribuzione dell'oggetto. Quando è true, il contenuto dell'array è spaziato alla larghezza massima dell'oggetto array.

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
public abstract int getRowSpacingRule()
```

Il tipo di spaziatura verticale tra gli elementi dell'array

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
public abstract void setRowSpacingRule(int value)
```

Il tipo di spaziatura verticale tra gli elementi dell'array

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
public abstract long getRowSpacing()
```

Spaziatura tra le righe di un array. È usata solo quando RowSpacingRule è impostato a 3 Exactly, nel qual caso l'unità di misura è punti, o Multiple, nel qual caso l'unità di misura è mezze linee. Valore predefinito: 0

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
public abstract void setRowSpacing(long value)
```

Spaziatura tra le righe di un array. È usata solo quando RowSpacingRule è impostato a 3 Exactly, nel qual caso l'unità di misura è punti, o Multiple, nel qual caso l'unità di misura è mezze linee. Valore predefinito: 0

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