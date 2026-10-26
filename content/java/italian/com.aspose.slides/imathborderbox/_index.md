---
title: IMathBorderBox
second_title: Riferimento API di Aspose.Slides per Java
description: Disegna un bordo rettangolare o di altro tipo intorno a IMathElement.
type: docs
url: /it/com.aspose.slides/imathborderbox/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBorderBox extends IMathElement
```

Disegna un bordo rettangolare o di altro tipo intorno a IMathElement.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBase()](#getBase--) | Argomento di base |
| [getHideTop()](#getHideTop--) | Nascondi margine superiore (predefinito è false) - specifica lo stato nascosto o mostrato del margine superiore del riquadro del bordo. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Nascondi margine superiore (predefinito è false) - specifica lo stato nascosto o mostrato del margine superiore del riquadro del bordo. |
| [getHideBottom()](#getHideBottom--) | Nascondi margine inferiore (predefinito è false) - specifica lo stato nascosto o mostrato del margine inferiore del riquadro del bordo. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Nascondi margine inferiore (predefinito è false) - specifica lo stato nascosto o mostrato del margine inferiore del riquadro del bordo. |
| [getHideLeft()](#getHideLeft--) | Nascondi margine sinistro (predefinito è false) - specifica lo stato nascosto o mostrato del margine sinistro del riquadro del bordo. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Nascondi margine sinistro (predefinito è false) - specifica lo stato nascosto o mostrato del margine sinistro del riquadro del bordo. |
| [getHideRight()](#getHideRight--) | Nascondi margine destro (predefinito è false) - specifica lo stato nascosto o mostrato del margine destro del riquadro del bordo. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Nascondi margine destro (predefinito è false) - specifica lo stato nascosto o mostrato del margine destro del riquadro del bordo. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Barrato orizzontale (predefinito è false) - specifica lo stato nascosto o mostrato di una linea orizzontale barrata. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Barrato orizzontale (predefinito è false) - specifica lo stato nascosto o mostrato di una linea orizzontale barrata. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Barrato verticale (predefinito è false) - specifica lo stato nascosto o mostrato di una linea verticale barrata. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Barrato verticale (predefinito è false) - specifica lo stato nascosto o mostrato di una linea verticale barrata. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Barrato dalla parte inferiore sinistra alla parte superiore destra (predefinito è false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Barrato dalla parte inferiore sinistra alla parte superiore destra (predefinito è false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Barrato dalla parte superiore sinistra alla parte inferiore destra (predefinito è false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Barrato dalla parte superiore sinistra alla parte inferiore destra (predefinito è false). |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Argomento di base

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  IMathElement base = borderBox.getBase();
>  ```

**Restituisce:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public abstract boolean getHideTop()
```


Nascondi margine superiore (predefinito è false) - specifica lo stato nascosto o mostrato del margine superiore del riquadro del bordo.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**Restituisce:**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public abstract void setHideTop(boolean value)
```


Nascondi margine superiore (predefinito è false) - specifica lo stato nascosto o mostrato del margine superiore del riquadro del bordo.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public abstract boolean getHideBottom()
```


Nascondi margine inferiore (predefinito è false) - specifica lo stato nascosto o mostrato del margine inferiore del riquadro del bordo.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**Restituisce:**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public abstract void setHideBottom(boolean value)
```


Nascondi margine inferiore (predefinito è false) - specifica lo stato nascosto o mostrato del margine inferiore del riquadro del bordo.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public abstract boolean getHideLeft()
```


Nascondi margine sinistro (predefinito è false) - specifica lo stato nascosto o mostrato del margine sinistro del riquadro del bordo.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**Restituisce:**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public abstract void setHideLeft(boolean value)
```


Nascondi margine sinistro (predefinito è false) - specifica lo stato nascosto o mostrato del margine sinistro del riquadro del bordo.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public abstract boolean getHideRight()
```


Nascondi margine destro (predefinito è false) - specifica lo stato nascosto o mostrato del margine destro del riquadro del bordo.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**Restituisce:**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public abstract void setHideRight(boolean value)
```


Nascondi margine destro (predefinito è false) - specifica lo stato nascosto o mostrato del margine destro del riquadro del bordo.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public abstract boolean getStrikethroughHorizontal()
```


Barrato orizzontale (predefinito è false) - specifica lo stato nascosto o mostrato di una linea orizzontale barrata.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Restituisce:**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public abstract void setStrikethroughHorizontal(boolean value)
```


Barrato orizzontale (predefinito è false) - specifica lo stato nascosto o mostrato di una linea orizzontale barrata.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public abstract boolean getStrikethroughVertical()
```


Barrato verticale (predefinito è false) - specifica lo stato nascosto o mostrato di una linea verticale barrata.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**Restituisce:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public abstract void setStrikethroughVertical(boolean value)
```


Barrato verticale (predefinito è false) - specifica lo stato nascosto o mostrato di una linea verticale barrata.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public abstract boolean getStrikethroughBottomLeftToTopRight()
```


Barrato dalla parte inferiore sinistra alla parte superiore destra (predefinito è false). Specifica lo stato nascosto o mostrato di una linea diagonale barrata dal bordo inferiore sinistro al bordo superiore destro del riquadro del bordo.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Restituisce:**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public abstract void setStrikethroughBottomLeftToTopRight(boolean value)
```


Barrato dalla parte inferiore sinistra alla parte superiore destra (predefinito è false). Specifica lo stato nascosto o mostrato di una linea diagonale barrata dal bordo inferiore sinistro al bordo superiore destro del riquadro del bordo.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public abstract boolean getStrikethroughTopLeftToBottomRight()
```


Barrato dalla parte superiore sinistra alla parte inferiore destra (predefinito è false). Specifica lo stato nascosto o mostrato di una linea diagonale barrata dal bordo superiore sinistro al bordo inferiore destro del riquadro del bordo.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Restituisce:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public abstract void setStrikethroughTopLeftToBottomRight(boolean value)
```


Barrato dalla parte superiore sinistra alla parte inferiore destra (predefinito è false). Specifica lo stato nascosto o mostrato di una linea diagonale barrata dal bordo superiore sinistro al bordo inferiore destro del riquadro del bordo.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |