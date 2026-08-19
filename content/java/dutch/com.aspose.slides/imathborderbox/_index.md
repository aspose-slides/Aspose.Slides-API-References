---
title: IMathBorderBox
second_title: Aspose.Slides voor Java API-referentie
description: Tekent een rechthoekige of andere rand rond de IMathElement.
type: docs
url: /nl/com.aspose.slides/imathborderbox/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBorderBox extends IMathElement
```

Tekent een rechthoekige of andere rand rond de IMathElement.

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
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Doorhalen horizontaal (standaard is false) - specificeert de verborgen of getoonde status van een horizontale doorhalingslijn. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Doorhalen horizontaal (standaard is false) - specificeert de verborgen of getoonde status van een horizontale doorhalingslijn. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Doorhalen verticaal (standaard is false) - specificeert de verborgen of getoonde status van een verticale doorhalingslijn. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Doorhalen verticaal (standaard is false) - specificeert de verborgen of getoonde status van een verticale doorhalingslijn. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Doorhalen onderkant-links naar bovenkant-rechts (standaard is false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Doorhalen onderkant-links naar bovenkant-rechts (standaard is false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Doorhalen bovenkant-links naar onderkant-rechts (standaard is false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Doorhalen bovenkant-links naar onderkant-rechts (standaard is false). |
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

**Retourneert:**
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

**Retourneert:**
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
| Parameter | Type | Beschrijving |
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

**Retourneert:**
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
| Parameter | Type | Beschrijving |
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

**Retourneert:**
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
| Parameter | Type | Beschrijving |
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

**Retourneert:**
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public abstract boolean getStrikethroughHorizontal()
```

Doorhalen horizontaal (standaard is false) - specificeert de verborgen of getoonde status van een horizontale doorhalingslijn.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Retourneert:**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public abstract void setStrikethroughHorizontal(boolean value)
```

Doorhalen horizontaal (standaard is false) - specificeert de verborgen of getoonde status van een horizontale doorhalingslijn.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public abstract boolean getStrikethroughVertical()
```

Doorhalen verticaal (standaard is false) - specificeert de verborgen of getoonde status van een verticale doorhalingslijn.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**Retourneert:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public abstract void setStrikethroughVertical(boolean value)
```

Doorhalen verticaal (standaard is false) - specificeert de verborgen of getoonde status van een verticale doorhalingslijn.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public abstract boolean getStrikethroughBottomLeftToTopRight()
```

Doorhalen onderkant-links naar bovenkant-rechts (standaard is false). Specificeert de verborgen of getoonde status van een diagonale doorhalingslijn van de onderkant-links naar de bovenkant-rechts van de randbox.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Retourneert:**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public abstract void setStrikethroughBottomLeftToTopRight(boolean value)
```

Doorhalen onderkant-links naar bovenkant-rechts (standaard is false). Specificeert de verborgen of getoonde status van een diagonale doorhalingslijn van de onderkant-links naar de bovenkant-rechts van de randbox.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public abstract boolean getStrikethroughTopLeftToBottomRight()
```

Doorhalen bovenkant-links naar onderkant-rechts (standaard is false). Specificeert de verborgen of getoonde status van een diagonale doorhalingslijn van de bovenkant-links naar de onderkant-rechts van de randbox.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Retourneert:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public abstract void setStrikethroughTopLeftToBottomRight(boolean value)
```

Doorhalen bovenkant-links naar onderkant-rechts (standaard is false). Specificeert de verborgen of getoonde status van een diagonale doorhalingslijn van de bovenkant-links naar de onderkant-rechts van de randbox.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |