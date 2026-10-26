---
title: MathBorderBox
second_title: Riferimento API Aspose.Slides per Java
description: Disegna un bordo rettangolare o di altro tipo intorno a IMathElement.
type: docs
url: /it/com.aspose.slides/mathborderbox/
---
**Eredita da:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Tutte le interfacce implementate:**
[com.aspose.slides.IMathBorderBox](../../com.aspose.slides/imathborderbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBorderBox extends MathElementBase implements IMathBorderBox, IHasControlCharacterProperties
```

Disegna un bordo rettangolare o di altro tipo attorno a IMathElement.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MathBorderBox(IMathElement element)](#MathBorderBox-com.aspose.slides.IMathElement-) | Crea un elemento MathBorderBox con bordo rettangolare |
| [MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Crea un elemento MathBorderBox |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBase()](#getBase--) | Argomento di base |
| [getHideTop()](#getHideTop--) | Nascondi bordo superiore (il valore predefinito è false) – specifica lo stato nascosto o mostrato del bordo superiore della casella. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Nascondi bordo superiore (il valore predefinito è false) – specifica lo stato nascosto o mostrato del bordo superiore della casella. |
| [getHideBottom()](#getHideBottom--) | Nascondi bordo inferiore (il valore predefinito è false) – specifica lo stato nascosto o mostrato del bordo inferiore della casella. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Nascondi bordo inferiore (il valore predefinito è false) – specifica lo stato nascosto o mostrato del bordo inferiore della casella. |
| [getHideLeft()](#getHideLeft--) | Nascondi bordo sinistro (il valore predefinito è false) – specifica lo stato nascosto o mostrato del bordo sinistro della casella. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Nascondi bordo sinistro (il valore predefinito è false) – specifica lo stato nascosto o mostrato del bordo sinistro della casella. |
| [getHideRight()](#getHideRight--) | Nascondi bordo destro (il valore predefinito è false) – specifica lo stato nascosto o mostrato del bordo destro della casella. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Nascondi bordo destro (il valore predefinito è false) – specifica lo stato nascosto o mostrato del bordo destro della casella. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Barra orizzontale (il valore predefinito è false) – specifica lo stato nascosto o mostrato di una linea orizzontale barrata. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Barra orizzontale (il valore predefinito è false) – specifica lo stato nascosto o mostrato di una linea orizzontale barrata. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Barra verticale (il valore predefinito è false) – specifica lo stato nascosto o mostrato di una linea verticale barrata. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Barra verticale (il valore predefinito è false) – specifica lo stato nascosto o mostrato di una linea verticale barrata. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Barra diagonale da basso a sinistra a alto a destra (il valore predefinito è false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Barra diagonale da basso a sinistra a alto a destra (il valore predefinito è false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Barra diagonale da alto a sinistra a basso a destra (il valore predefinito è false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Barra diagonale da alto a sinistra a basso a destra (il valore predefinito è false). |
| [getChildren()](#getChildren--) | Ottieni gli elementi figli |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Proprietà del carattere di controllo |
### MathBorderBox(IMathElement element) {#MathBorderBox-com.aspose.slides.IMathElement-}
```
public MathBorderBox(IMathElement element)
```


Crea un elemento MathBorderBox con bordo rettangolare

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | L'elemento base a cui viene applicata la casella di bordo. Può essere nullo. |

### MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


Crea un elemento MathBorderBox

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"), true, true, true, false, true, true, true, true)
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | L'elemento base a cui viene applicata la casella di bordo |
| hideTop | boolean | Nascondi bordo superiore |
| hideBottom | boolean | Nascondi bordo inferiore |
| hideLeft | boolean | Nascondi bordo sinistro |
| hideRight | boolean | Nascondi bordo destro |
| strikethroughHorizontal | boolean | Barra orizzontale |
| strikethroughVertical | boolean | Barra verticale |
| strikethroughBottomLeftToTopRight | boolean | Barra diagonale da basso a sinistra a alto a destra |
| strikethroughTopLeftToBottomRight | boolean | Barra diagonale da alto a sinistra a basso a destra |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Argomento di base

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  IMathElement base = borderBox.getBase();
> ```

**Restituisce:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public final boolean getHideTop()
```


Nascondi bordo superiore (il valore predefinito è false) – specifica lo stato nascosto o mostrato del bordo superiore della casella.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**Restituisce:**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public final void setHideTop(boolean value)
```


Nascondi bordo superiore (il valore predefinito è false) – specifica lo stato nascosto o mostrato del bordo superiore della casella.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public final boolean getHideBottom()
```


Nascondi bordo inferiore (il valore predefinito è false) – specifica lo stato nascosto o mostrato del bordo inferiore della casella.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**Restituisce:**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public final void setHideBottom(boolean value)
```


Nascondi bordo inferiore (il valore predefinito è false) – specifica lo stato nascosto o mostrato del bordo inferiore della casella.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public final boolean getHideLeft()
```


Nascondi bordo sinistro (il valore predefinito è false) – specifica lo stato nascosto o mostrato del bordo sinistro della casella.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**Restituisce:**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public final void setHideLeft(boolean value)
```


Nascondi bordo sinistro (il valore predefinito è false) – specifica lo stato nascosto o mostrato del bordo sinistro della casella.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public final boolean getHideRight()
```


Nascondi bordo destro (il valore predefinito è false) – specifica lo stato nascosto o mostrato del bordo destro della casella.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**Restituisce:**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public final void setHideRight(boolean value)
```


Nascondi bordo destro (il valore predefinito è false) – specifica lo stato nascosto o mostrato del bordo destro della casella.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public final boolean getStrikethroughHorizontal()
```


Barra orizzontale (il valore predefinito è false) – specifica lo stato nascosto o mostrato di una linea orizzontale barrata.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Restituisce:**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public final void setStrikethroughHorizontal(boolean value)
```


Barra orizzontale (il valore predefinito è false) – specifica lo stato nascosto o mostrato di una linea orizzontale barrata.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public final boolean getStrikethroughVertical()
```


Barra verticale (il valore predefinito è false) – specifica lo stato nascosto o mostrato di una linea verticale barrata.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**Restituisce:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public final void setStrikethroughVertical(boolean value)
```


Barra verticale (il valore predefinito è false) – specifica lo stato nascosto o mostrato di una linea verticale barrata.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public final boolean getStrikethroughBottomLeftToTopRight()
```


Barra diagonale da basso a sinistra a alto a destra (il valore predefinito è false). Specifica lo stato nascosto o mostrato di una linea diagonale barrata dal bordo inferiore sinistro a quello superiore destro della casella.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Restituisce:**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public final void setStrikethroughBottomLeftToTopRight(boolean value)
```


Barra diagonale da basso a sinistra a alto a destra (il valore predefinito è false). Specifica lo stato nascosto o mostrato di una linea diagonale barrata dal bordo inferiore sinistro a quello superiore destro della casella.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public final boolean getStrikethroughTopLeftToBottomRight()
```


Barra diagonale da alto a sinistra a basso a destra (il valore predefinito è false). Specifica lo stato nascosto o mostrato di una linea diagonale barrata dal bordo superiore sinistro a quello inferiore destro della casella.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Restituisce:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public final void setStrikethroughTopLeftToBottomRight(boolean value)
```


Barra diagonale da alto a sinistra a basso a destra (il valore predefinito è false). Specifica lo stato nascosto o mostrato di una linea diagonale barrata dal bordo superiore sinistro a quello inferiore destro della casella.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
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