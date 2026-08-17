---
title: IMathBorderBox
second_title: Aspose.Slides für Java API-Referenz
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
| [getHideTop()](#getHideTop--) | Obere Kante ausblenden (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand der oberen Kante des Rahmenkastens an. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Obere Kante ausblenden (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand der oberen Kante des Rahmenkastens an. |
| [getHideBottom()](#getHideBottom--) | Untere Kante ausblenden (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand der unteren Kante des Rahmenkastens an. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Untere Kante ausblenden (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand der unteren Kante des Rahmenkastens an. |
| [getHideLeft()](#getHideLeft--) | Linke Kante ausblenden (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand der linken Kante des Rahmenkastens an. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Linke Kante ausblenden (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand der linken Kante des Rahmenkastens an. |
| [getHideRight()](#getHideRight--) | Rechte Kante ausblenden (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand der rechten Kante des Rahmenkastens an. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Rechte Kante ausblenden (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand der rechten Kante des Rahmenkastens an. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Durchgestrichene horizontale Linie (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand einer durchgestrichenen horizontalen Linie an. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Durchgestrichene horizontale Linie (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand einer durchgestrichenen horizontalen Linie an. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Durchgestrichene vertikale Linie (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand einer durchgestrichenen vertikalen Linie an. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Durchgestrichene vertikale Linie (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand einer durchgestrichenen vertikalen Linie an. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Durchgestrichene Diagonale von unten links nach oben rechts (Standard ist false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Durchgestrichene Diagonale von unten links nach oben rechts (Standard ist false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Durchgestrichene Diagonale von oben links nach unten rechts (Standard ist false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Durchgestrichene Diagonale von oben links nach unten rechts (Standard ist false). |
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

Obere Kante ausblenden (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand der oberen Kante des Rahmenkastens an.

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

Obere Kante ausblenden (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand der oberen Kante des Rahmenkastens an.

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

Untere Kante ausblenden (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand der unteren Kante des Rahmenkastens an.

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

Untere Kante ausblenden (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand der unteren Kante des Rahmenkastens an.

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

Linke Kante ausblenden (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand der linken Kante des Rahmenkastens an.

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

Linke Kante ausblenden (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand der linken Kante des Rahmenkastens an.

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

Rechte Kante ausblenden (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand der rechten Kante des Rahmenkastens an.

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

Rechte Kante ausblenden (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand der rechten Kante des Rahmenkastens an.

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

Durchgestrichene horizontale Linie (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand einer durchgestrichenen horizontalen Linie an.

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

Durchgestrichene horizontale Linie (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand einer durchgestrichenen horizontalen Linie an.

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

Durchgestrichene vertikale Linie (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand einer durchgestrichenen vertikalen Linie an.

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

Durchgestrichene vertikale Linie (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand einer durchgestrichenen vertikalen Linie an.

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

Durchgestrichene Diagonale von unten links nach oben rechts (Standard ist false). Gibt den ausgeblendeten oder angezeigten Zustand einer durchgestrichenen diagonalen Linie von der unteren linken Ecke zur oberen rechten Ecke des Rahmenkastens an.

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

Durchgestrichene Diagonale von unten links nach oben rechts (Standard ist false). Gibt den ausgeblendeten oder angezeigten Zustand einer durchgestrichenen diagonalen Linie von der unteren linken Ecke zur oberen rechten Ecke des Rahmenkastens an.

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

Durchgestrichene Diagonale von oben links nach unten rechts (Standard ist false). Gibt den ausgeblendeten oder angezeigten Zustand einer durchgestrichenen diagonalen Linie von der oberen linken Ecke zur unteren rechten Ecke des Rahmenkastens an.

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

Durchgestrichene Diagonale von oben links nach unten rechts (Standard ist false). Gibt den ausgeblendeten oder angezeigten Zustand einer durchgestrichenen diagonalen Linie von der oberen linken Ecke zur unteren rechten Ecke des Rahmenkastens an.

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