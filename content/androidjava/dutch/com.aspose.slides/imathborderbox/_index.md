---
title: IMathBorderBox
second_title: Aspose.Slides voor Android via Java API-referentie
description: Tekent een rechthoek of een andere rand rond de IMathElement.
type: docs
url: /nl/com.aspose.slides/imathborderbox/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBorderBox extends IMathElement
```

Tekent een rechthoekige of een andere rand rond de IMathElement.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getBase()](#getBase--) | Basisargument |
| [getHideTop()](#getHideTop--) | Verberg bovenrand (standaard is false) - specificeert de verborgen of getoonde status van de bovenrand van de randbox. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Verberg bovenrand (standaard is false) - specificeert de verborgen of getoonde status van de bovenrand van de randbox. |
| [getHideBottom()](#getHideBottom--) | Verberg onderrand (standaard is false) - specificeert de verborgen of getoonde status van de onderrand van de randbox. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Verberg onderrand (standaard is false) - specificeert de verborgen of getoonde status van de onderrand van de randbox. |
| [getHideLeft()](#getHideLeft--) | Verberg linkerrand (standaard is false) - specificeert de verborgen of getoonde status van de linkerrand van de randbox. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Verberg linkerrand (standaard is false) - specificeert de verborgen of getoonde status van de linkerrand van de randbox. |
| [getHideRight()](#getHideRight--) | Verberg rechterrand (standaard is false) - specificeert de verborgen of getoonde status van de rechterrand van de randbox. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Verberg rechterrand (standaard is false) - specificeert de verborgen of getoonde status van de rechterrand van de randbox. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Doorhalen horizontaal (standaard is false) - specificeert de verborgen of getoonde status van een horizontale doorhaallijn. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Doorhalen horizontaal (standaard is false) - specificeert de verborgen of getoonde status van een horizontale doorhaallijn. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Doorhalen verticaal (standaard is false) - specificeert de verborgen of getoonde status van een verticale doorhaallijn. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Doorhalen verticaal (standaard is false) - specificeert de verborgen of getoonde status van een verticale doorhaallijn. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Doorhalen van linksonder naar rechtsboven (standaard is false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Doorhalen van linksonder naar rechtsboven (standaard is false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Doorhalen van linksboven naar rechtsonder (standaard is false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Doorhalen van linksboven naar rechtsonder (standaard is false). |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Basisargument

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  IMathElement base = borderBox.getBase();
> ```

**Retour:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public abstract boolean getHideTop()
```


Verberg bovenrand (standaard is false) - specificeert de verborgen of getoonde status van de bovenrand van de randbox.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**Retour:**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public abstract void setHideTop(boolean value)
```


Verberg bovenrand (standaard is false) - specificeert de verborgen of getoonde status van de bovenrand van de randbox.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public abstract boolean getHideBottom()
```


Verberg onderrand (standaard is false) - specificeert de verborgen of getoonde status van de onderrand van de randbox.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**Retour:**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public abstract void setHideBottom(boolean value)
```


Verberg onderrand (standaard is false) - specificeert de verborgen of getoonde status van de onderrand van de randbox.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public abstract boolean getHideLeft()
```


Verberg linkerrand (standaard is false) - specificeert de verborgen of getoonde status van de linkerrand van de randbox.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**Retour:**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public abstract void setHideLeft(boolean value)
```


Verberg linkerrand (standaard is false) - specificeert de verborgen of getoonde status van de linkerrand van de randbox.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public abstract boolean getHideRight()
```


Verberg rechterrand (standaard is false) - specificeert de verborgen of getoonde status van de rechterrand van de randbox.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**Retour:**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public abstract void setHideRight(boolean value)
```


Verberg rechterrand (standaard is false) - specificeert de verborgen of getoonde status van de rechterrand van de randbox.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public abstract boolean getStrikethroughHorizontal()
```


Doorhalen horizontaal (standaard is false) - specificeert de verborgen of getoonde status van een horizontale doorhaallijn.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Retour:**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public abstract void setStrikethroughHorizontal(boolean value)
```


Doorhalen horizontaal (standaard is false) - specificeert de verborgen of getoonde status van een horizontale doorhaallijn.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public abstract boolean getStrikethroughVertical()
```


Doorhalen verticaal (standaard is false) - specificeert de verborgen of getoonde status van een verticale doorhaallijn.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**Retour:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public abstract void setStrikethroughVertical(boolean value)
```


Doorhalen verticaal (standaard is false) - specificeert de verborgen of getoonde status van een verticale doorhaallijn.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public abstract boolean getStrikethroughBottomLeftToTopRight()
```


Doorhalen van linksonder naar rechtsboven (standaard is false). Specificeert de verborgen of getoonde status van een diagonale doorhaallijn van de linksonderhoek naar de rechtsbovenhoek van de randbox.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Retour:**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public abstract void setStrikethroughBottomLeftToTopRight(boolean value)
```


Doorhalen van linksonder naar rechtsboven (standaard is false). Specificeert de verborgen of getoonde status van een diagonale doorhaallijn van de linksonderhoek naar de rechtsbovenhoek van de randbox.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public abstract boolean getStrikethroughTopLeftToBottomRight()
```


Doorhalen van linksboven naar rechtsonder (standaard is false). Specificeert de verborgen of getoonde status van een diagonale doorhaallijn van de linkerbovenhoek naar de rechteronderhoek van de randbox.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Retour:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public abstract void setStrikethroughTopLeftToBottomRight(boolean value)
```


Doorhalen van linksboven naar rechtsonder (standaard is false). Specificeert de verborgen of getoonde status van een diagonale doorhaallijn van de linkerbovenhoek naar de rechteronderhoek van de randbox.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |