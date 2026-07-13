---
title: MathBorderBox
second_title: Riferimento API di Aspose.Slides per Android via Java
description: Disegna un bordo rettangolare o un altro tipo di bordo attorno a IMathElement.
type: docs
url: /it/com.aspose.slides/mathborderbox/
---
**Ereditarietà:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Tutte le interfacce implementate:**
[com.aspose.slides.IMathBorderBox](../../com.aspose.slides/imathborderbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBorderBox extends MathElementBase implements IMathBorderBox, IHasControlCharacterProperties
```

Disegna un bordo rettangolare o un altro tipo di bordo attorno a IMathElement.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MathBorderBox(IMathElement element)](#MathBorderBox-com.aspose.slides.IMathElement-) | Crea l'elemento MathBorderBox con bordo rettangolare |
| [MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Crea l'elemento MathBorderBox |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBase()](#getBase--) | Argomento di base |
| [getHideTop()](#getHideTop--) | Nascondi bordo superiore (default is false) - specifica lo stato nascosto o mostrato del bordo superiore della casella del bordo. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Nascondi bordo superiore (default is false) - specifica lo stato nascosto o mostrato del bordo superiore della casella del bordo. |
| [getHideBottom()](#getHideBottom--) | Nascondi bordo inferiore (default is false) - specifica lo stato nascosto o mostrato del bordo inferiore della casella del bordo. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Nascondi bordo inferiore (default is false) - specifica lo stato nascosto o mostrato del bordo inferiore della casella del bordo. |
| [getHideLeft()](#getHideLeft--) | Nascondi bordo sinistro (default is false) - specifica lo stato nascosto o mostrato del bordo sinistro della casella del bordo. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Nascondi bordo sinistro (default is false) - specifica lo stato nascosto o mostrato del bordo sinistro della casella del bordo. |
| [getHideRight()](#getHideRight--) | Nascondi bordo destro (default is false) - specifica lo stato nascosto o mostrato del bordo destro della casella del bordo. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Nascondi bordo destro (default is false) - specifica lo stato nascosto o mostrato del bordo destro della casella del bordo. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Barrato orizzontale (default is false) - specifica lo stato nascosto o mostrato di una linea orizzontale barrata. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Barrato orizzontale (default is false) - specifica lo stato nascosto o mostrato di una linea orizzontale barrata. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Barrato verticale (default is false) - specifica lo stato nascosto o mostrato di una linea verticale barrata. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Barrato verticale (default is false) - specifica lo stato nascosto o mostrato di una linea verticale barrata. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Barrato da basso-sinistra a alto-destra (default is false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Barrato da basso-sinistra a alto-destra (default is false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Barrato da alto-sinistra a basso-destra (default is false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Barrato da alto-sinistra a basso-destra (default is false). |
| [getChildren()](#getChildren--) | Ottieni gli elementi figli |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Proprietà dei caratteri di controllo |
### MathBorderBox(IMathElement element) {#MathBorderBox-com.aspose.slides.IMathElement-}
```
public MathBorderBox(IMathElement element)
```


Crea l'elemento MathBorderBox con bordo rettangolare

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | L'elemento base a cui viene applicata la casella del bordo. Può essere null. |

### MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


Crea l'elemento MathBorderBox

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"), true, true, true, false, true, true, true, true)
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | L'elemento base a cui viene applicata la casella del bordo |
| hideTop | boolean | Nascondi bordo superiore |
| hideBottom | boolean | Nascondi bordo inferiore |
| hideLeft | boolean | Nascondi bordo sinistro |
| hideRight | boolean | Nascondi bordo destro |
| strikethroughHorizontal | boolean | Barrato orizzontale |
| strikethroughVertical | boolean | Barrato verticale |
| strikethroughBottomLeftToTopRight | boolean | Barrato da basso-sinistra a alto-destra |
| strikethroughTopLeftToBottomRight | boolean | Barrato da alto-sinistra a basso-destra |

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


Nascondi bordo superiore (default is false) - specifica lo stato nascosto o mostrato del bordo superiore della casella del bordo.

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


Nascondi bordo superiore (default is false) - specifica lo stato nascosto o mostrato del bordo superiore della casella del bordo.

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


Nascondi bordo inferiore (default is false) - specifica lo stato nascosto o mostrato del bordo inferiore della casella del bordo.

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


Nascondi bordo inferiore (default is false) - specifica lo stato nascosto o mostrato del bordo inferiore della casella del bordo.

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


Nascondi bordo sinistro (default is false) - specifica lo stato nascosto o mostrato del bordo sinistro della casella del bordo.

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


Nascondi bordo sinistro (default is false) - specifica lo stato nascosto o mostrato del bordo sinistro della casella del bordo.

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


Nascondi bordo destro (default is false) - specifica lo stato nascosto o mostrato del bordo destro della casella del bordo.

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


Nascondi bordo destro (default is false) - specifica lo stato nascosto o mostrato del bordo destro della casella del bordo.

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


Barrato orizzontale (default is false) - specifica lo stato nascosto o mostrato di una linea orizzontale barrata.

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


Barrato orizzontale (default is false) - specifica lo stato nascosto o mostrato di una linea orizzontale barrata.

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


Barrato verticale (default is false) - specifica lo stato nascosto o mostrato di una linea verticale barrata.

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


Barrato verticale (default is false) - specifica lo stato nascosto o mostrato di una linea verticale barrata.

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


Barrato da basso-sinistra a alto-destra (default is false). Specifica lo stato nascosto o mostrato di una linea diagonale barrata dal angolo in basso a sinistra a quello in alto a destra della casella del bordo.

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


Barrato da basso-sinistra a alto-destra (default is false). Specifica lo stato nascosto o mostrato di una linea diagonale barrata dal angolo in basso a sinistra a quello in alto a destra della casella del bordo.

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


Barrato da alto-sinistra a basso-destra (default is false). Specifica lo stato nascosto o mostrato di una linea diagonale barrata dal angolo in alto a sinistra a quello in basso a destra della casella del bordo.

--------------------

> ```
> Esempio:
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


Barrato da alto-sinistra a basso-destra (default is false). Specifica lo stato nascosto o mostrato di una linea diagonale barrata dal angolo in alto a sinistra a quello in basso a destra della casella del bordo.

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


Proprietà dei caratteri di controllo

**Restituisce:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps