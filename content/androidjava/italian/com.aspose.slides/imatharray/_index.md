---
title: IMathArray
second_title: Riferimento API Java di Aspose.Slides per Android
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
| [getArguments()](#getArguments--) | Il set di elementi dell'array |
| [getBaseJustification()](#getBaseJustification--) | Specifica l'allineamento dell'array rispetto al testo circostante. Il testo esterno all'array può essere allineato con il bottom, top o center di un oggetto array. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Specifica l'allineamento dell'array rispetto al testo circostante. Il testo esterno all'array può essere allineato con il bottom, top o center di un oggetto array. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Maximum Distribution Se true, l'array è distribuito alla larghezza massima dell'elemento contenitore (page, column, cell, ecc.). |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Maximum Distribution Se true, l'array è distribuito alla larghezza massima dell'elemento contenitore (page, column, cell, ecc.). |
| [getObjectDistribution()](#getObjectDistribution--) | Object Distribution Se true, il contenuto dell'array è distribuito alla larghezza massima dell'oggetto array. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Object Distribution Se true, il contenuto dell'array è distribuito alla larghezza massima dell'oggetto array. |
| [getRowSpacingRule()](#getRowSpacingRule--) | Il tipo di spaziatura verticale tra gli elementi dell'array |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | Il tipo di spaziatura verticale tra gli elementi dell'array |
| [getRowSpacing()](#getRowSpacing--) | Spaziatura tra le righe di un array. È usata solo quando RowSpacingRule è impostato a 3 Exactly, nel qual caso l'unità di misura è points o Multiple, nel qual caso l'unità di misura è half-lines. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Spaziatura tra le righe di un array. È usata solo quando RowSpacingRule è impostato a 3 Exactly, nel qual caso l'unità di misura è points o Multiple, nel qual caso l'unità di misura è half-lines. |
### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
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
public abstract int getBaseJustification()
```

Specifică l'allineamento dell'array rispetto al testo circostante. Il testo esterno all'array può essere allineato con il bottom, top o center di un oggetto array. Valore predefinito: Center

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

Specifică l'allineamento dell'array rispetto al testo circostante. Il testo esterno all'array può essere allineato con il bottom, top o center di un oggetto array. Valore predefinito: Center

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

Maximum Distribution Se true, l'array è distribuito alla larghezza massima dell'elemento contenitore (page, column, cell, ecc.).

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

Maximum Distribution Se true, l'array è distribuito alla larghezza massima dell'elemento contenitore (page, column, cell, ecc.).

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

Object Distribution Se true, il contenuto dell'array è distribuito alla larghezza massima dell'oggetto array.

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

Object Distribution Se true, il contenuto dell'array è distribuito alla larghezza massima dell'oggetto array.

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

Spaziatura tra le righe di un array. È usata solo quando RowSpacingRule è impostato a 3 Exactly, nel qual caso l'unità di misura è points o Multiple, nel qual caso l'unità di misura è half-lines. Valore predefinito: 0

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

Spaziatura tra le righe di un array. È usata solo quando RowSpacingRule è impostato a 3 Exactly, nel qual caso l'unità di misura è points o Multiple, nel qual caso l'unità di misura è half-lines. Valore predefinito: 0

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