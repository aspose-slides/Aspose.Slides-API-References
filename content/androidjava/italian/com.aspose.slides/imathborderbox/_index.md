---
title: IMathBorderBox
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Disegna un bordo rettangolare o di altro tipo attorno a IMathElement.
type: docs
url: /it/com.aspose.slides/imathborderbox/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBorderBox extends IMathElement
```

Disegna un bordo rettangolare o un altro tipo di bordo attorno a IMathElement.

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
| [getHideTop()](#getHideTop--) | Nascondi il bordo superiore (predefinito è false) - specifica lo stato nascosto o mostrato del bordo superiore della casella del bordo. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Nascondi il bordo superiore (predefinito è false) - specifica lo stato nascosto o mostrato del bordo superiore della casella del bordo. |
| [getHideBottom()](#getHideBottom--) | Nascondi il bordo inferiore (predefinito è false) - specifica lo stato nascosto o mostrato del bordo inferiore della casella del bordo. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Nascondi il bordo inferiore (predefinito è false) - specifica lo stato nascosto o mostrato del bordo inferiore della casella del bordo. |
| [getHideLeft()](#getHideLeft--) | Nascondi il bordo sinistro (predefinito è false) - specifica lo stato nascosto o mostrato del bordo sinistro della casella del bordo. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Nascondi il bordo sinistro (predefinito è false) - specifica lo stato nascosto o mostrato del bordo sinistro della casella del bordo. |
| [getHideRight()](#getHideRight--) | Nascondi il bordo destro (predefinito è false) - specifica lo stato nascosto o mostrato del bordo destro della casella del bordo. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Nascondi il bordo destro (predefinito è false) - specifica lo stato nascosto o mostrato del bordo destro della casella del bordo. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Barrato orizzontale (predefinito è false) - specifica lo stato nascosto o mostrato di una linea orizzontale barrata. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Barrato orizzontale (predefinito è false) - specifica lo stato nascosto o mostrato di una linea orizzontale barrata. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Barrato verticale (predefinito è false) - specifica lo stato nascosto o mostrato di una linea verticale barrata. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Barrato verticale (predefinito è false) - specifica lo stato nascosto o mostrato di una linea verticale barrata. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Barrato dal basso sinistro al alto destro (predefinito è false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Barrato dal basso sinistro al alto destro (predefinito è false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Barrato dall'alto sinistro al basso destro (predefinito è false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Barrato dall'alto sinistro al basso destro (predefinito è false). |
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
> ```

**Restituisce:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public abstract boolean getHideTop()
```


Nascondi il bordo superiore (predefinito è false) - specifica lo stato nascosto o mostrato del bordo superiore della casella del bordo.

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


Nascondi il bordo superiore (predefinito è false) - specifica lo stato nascosto o mostrato del bordo superiore della casella del bordo.

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


Nascondi il bordo inferiore (predefinito è false) - specifica lo stato nascosto o mostrato del bordo inferiore della casella del bordo.

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


Nascondi il bordo inferiore (predefinito è false) - specifica lo stato nascosto o mostrato del bordo inferiore della casella del bordo.

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


Nascondi il bordo sinistro (predefinito è false) - specifica lo stato nascosto o mostrato del bordo sinistro della casella del bordo.

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


Nascondi il bordo sinistro (predefinito è false) - specifica lo stato nascosto o mostrato del bordo sinistro della casella del bordo.

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


Nascondi il bordo destro (predefinito è false) - specifica lo stato nascosto o mostrato del bordo destro della casella del bordo.

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


Nascondi il bordo destro (predefinito è false) - specifica lo stato nascosto o mostrato del bordo destro della casella del bordo.

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


Barrato dal basso sinistro al alto destro (predefinito è false). Specifica lo stato nascosto o mostrato di una linea diagonale barrata dal basso sinistro al alto destro della casella del bordo.

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


Barrato dal basso sinistro al alto destro (predefinito è false). Specifica lo stato nascosto o mostrato di una linea diagonale barrata dal basso sinistro al alto destro della casella del bordo.

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


Barrato dall'alto sinistro al basso destro (predefinito è false). Specifica lo stato nascosto o mostrato di una linea diagonale barrata dall'alto sinistro al basso destro della casella del bordo.

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


Barrato dall'alto sinistro al basso destro (predefinito è false). Specifica lo stato nascosto o mostrato di una linea diagonale barrata dall'alto sinistro al basso destro della casella del bordo.

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