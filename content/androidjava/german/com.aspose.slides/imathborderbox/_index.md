---
title: IMathBorderBox
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Zeichnet einen rechteckigen oder anderen Rand um das IMathElement.
type: docs
url: /de/com.aspose.slides/imathborderbox/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBorderBox extends IMathElement
```

Zeichnet einen rechteckigen oder anderen Rand um das IMathElement.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBase()](#getBase--) | Basisargument |
| [getHideTop()](#getHideTop--) | Obere Kante ausblenden (Standard ist false) – gibt an, ob die obere Kante des Randkastens verborgen oder angezeigt wird. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Obere Kante ausblenden (Standard ist false) – gibt an, ob die obere Kante des Randkastens verborgen oder angezeigt wird. |
| [getHideBottom()](#getHideBottom--) | Untere Kante ausblenden (Standard ist false) – gibt an, ob die untere Kante des Randkastens verborgen oder angezeigt wird. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Untere Kante ausblenden (Standard ist false) – gibt an, ob die untere Kante des Randkastens verborgen oder angezeigt wird. |
| [getHideLeft()](#getHideLeft--) | Linke Kante ausblenden (Standard ist false) – gibt an, ob die linke Kante des Randkastens verborgen oder angezeigt wird. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Linke Kante ausblenden (Standard ist false) – gibt an, ob die linke Kante des Randkastens verborgen oder angezeigt wird. |
| [getHideRight()](#getHideRight--) | Rechte Kante ausblenden (Standard ist false) – gibt an, ob die rechte Kante des Randkastens verborgen oder angezeigt wird. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Rechte Kante ausblenden (Standard ist false) – gibt an, ob die rechte Kante des Randkastens verborgen oder angezeigt wird. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Horizontale Durchstreichung (Standard ist false) – gibt an, ob eine horizontale Durchstreichung verborgen oder angezeigt wird. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Horizontale Durchstreichung (Standard ist false) – gibt an, ob eine horizontale Durchstreichung verborgen oder angezeigt wird. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Vertikale Durchstreichung (Standard ist false) – gibt an, ob eine vertikale Durchstreichung verborgen oder angezeigt wird. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Vertikale Durchstreichung (Standard ist false) – gibt an, ob eine vertikale Durchstreichung verborgen oder angezeigt wird. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Durchgestrichen von links unten nach rechts oben (Standard ist false) – gibt den verborgenen oder angezeigten Zustand einer diagonalen Durchstreichung von der linken unteren Ecke zur rechten oberen Ecke des Randkastens an. |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Durchgestrichen von links unten nach rechts oben (Standard ist false) – gibt den verborgenen oder angezeigten Zustand einer diagonalen Durchstreichung von der linken unteren Ecke zur rechten oberen Ecke des Randkastens an. |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Durchgestrichen von links oben nach rechts unten (Standard ist false) – gibt den verborgenen oder angezeigten Zustand einer diagonalen Durchstreichung von der linken oberen Ecke zur rechten unteren Ecke des Randkastens an. |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Durchgestrichen von links oben nach rechts unten (Standard ist false) – gibt den verborgenen oder angezeigten Zustand einer diagonalen Durchstreichung von der linken oberen Ecke zur rechten unteren Ecke des Randkastens an. |
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

**Rückgabe:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public abstract boolean getHideTop()
```

Obere Kante ausblenden (Standard ist false) – gibt an, ob die obere Kante des Randkastens verborgen oder angezeigt wird.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**Rückgabe:**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public abstract void setHideTop(boolean value)
```

Obere Kante ausblenden (Standard ist false) – gibt an, ob die obere Kante des Randkastens verborgen oder angezeigt wird.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getHideBottom() {#getHideBottom--}
```
public abstract boolean getHideBottom()
```

Untere Kante ausblenden (Standard ist false) – gibt an, ob die untere Kante des Randkastens verborgen oder angezeigt wird.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**Rückgabe:**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public abstract void setHideBottom(boolean value)
```

Untere Kante ausblenden (Standard ist false) – gibt an, ob die untere Kante des Randkastens verborgen oder angezeigt wird.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getHideLeft() {#getHideLeft--}
```
public abstract boolean getHideLeft()
```

Linke Kante ausblenden (Standard ist false) – gibt an, ob die linke Kante des Randkastens verborgen oder angezeigt wird.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**Rückgabe:**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public abstract void setHideLeft(boolean value)
```

Linke Kante ausblenden (Standard ist false) – gibt an, ob die linke Kante des Randkastens verborgen oder angezeigt wird.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getHideRight() {#getHideRight--}
```
public abstract boolean getHideRight()
```

Rechte Kante ausblenden (Standard ist false) – gibt an, ob die rechte Kante des Randkastens verborgen oder angezeigt wird.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**Rückgabe:**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public abstract void setHideRight(boolean value)
```

Rechte Kante ausblenden (Standard ist false) – gibt an, ob die rechte Kante des Randkastens verborgen oder angezeigt wird.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public abstract boolean getStrikethroughHorizontal()
```

Horizontale Durchstreichung (Standard ist false) – gibt an, ob eine horizontale Durchstreichung verborgen oder angezeigt wird.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Rückgabe:**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public abstract void setStrikethroughHorizontal(boolean value)
```

Horizontale Durchstreichung (Standard ist false) – gibt an, ob eine horizontale Durchstreichung verborgen oder angezeigt wird.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public abstract boolean getStrikethroughVertical()
```

Vertikale Durchstreichung (Standard ist false) – gibt an, ob eine vertikale Durchstreichung verborgen oder angezeigt wird.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**Rückgabe:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public abstract void setStrikethroughVertical(boolean value)
```

Vertikale Durchstreichung (Standard ist false) – gibt an, ob eine vertikale Durchstreichung verborgen oder angezeigt wird.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public abstract boolean getStrikethroughBottomLeftToTopRight()
```

Durchgestrichen von links unten nach rechts oben (Standard ist false) – gibt den verborgenen oder angezeigten Zustand einer diagonalen Durchstreichung von der linken unteren Ecke zur rechten oberen Ecke des Randkastens an.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Rückgabe:**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public abstract void setStrikethroughBottomLeftToTopRight(boolean value)
```

Durchgestrichen von links unten nach rechts oben (Standard ist false) – gibt den verborgenen oder angezeigten Zustand einer diagonalen Durchstreichung von der linken unteren Ecke zur rechten oberen Ecke des Randkastens an.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public abstract boolean getStrikethroughTopLeftToBottomRight()
```

Durchgestrichen von links oben nach rechts unten (Standard ist false) – gibt den verborgenen oder angezeigten Zustand einer diagonalen Durchstreichung von der linken oberen Ecke zur rechten unteren Ecke des Randkastens an.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Rückgabe:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public abstract void setStrikethroughTopLeftToBottomRight(boolean value)
```

Durchgestrichen von links oben nach rechts unten (Standard ist false) – gibt den verborgenen oder angezeigten Zustand einer diagonalen Durchstreichung von der linken oberen Ecke zur rechten unteren Ecke des Randkastens an.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
