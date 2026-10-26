---
title: MathBorderBox
second_title: Aspose.Slides für Java API-Referenz
description: Zeichnet einen rechteckigen oder anderen Rahmen um das IMathElement.
type: docs
url: /de/com.aspose.slides/mathborderbox/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathBorderBox](../../com.aspose.slides/imathborderbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBorderBox extends MathElementBase implements IMathBorderBox, IHasControlCharacterProperties
```

Zeichnet einen rechteckigen oder anderen Rahmen um das IMathElement.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MathBorderBox(IMathElement element)](#MathBorderBox-com.aspose.slides.IMathElement-) | Erstellt MathBorderBox-Element mit rechteckigem Rand |
| [MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Erstellt MathBorderBox-Element |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBase()](#getBase--) | Basisargument |
| [getHideTop()](#getHideTop--) | Obere Kante ausblenden (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand der oberen Kante des Randkastens an. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Obere Kante ausblenden (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand der oberen Kante des Randkastens an. |
| [getHideBottom()](#getHideBottom--) | Untere Kante ausblenden (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand der unteren Kante des Randkastens an. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Untere Kante ausblenden (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand der unteren Kante des Randkastens an. |
| [getHideLeft()](#getHideLeft--) | Linke Kante ausblenden (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand der linken Kante des Randkastens an. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Linke Kante ausblenden (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand der linken Kante des Randkastens an. |
| [getHideRight()](#getHideRight--) | Rechte Kante ausblenden (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand der rechten Kante des Randkastens an. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Rechte Kante ausblenden (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand der rechten Kante des Randkastens an. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Durchgestrichene horizontale Linie (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand einer durchgestrichenen horizontalen Linie an. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Durchgestrichene horizontale Linie (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand einer durchgestrichenen horizontalen Linie an. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Durchgestrichene vertikale Linie (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand einer durchgestrichenen vertikalen Linie an. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Durchgestrichene vertikale Linie (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand einer durchgestrichenen vertikalen Linie an. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Durchgestrichene diagonale Linie von unten links nach oben rechts (Standard ist false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Durchgestrichene diagonale Linie von unten links nach oben rechts (Standard ist false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Durchgestrichene diagonale Linie von oben links nach unten rechts (Standard ist false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Durchgestrichene diagonale Linie von oben links nach unten rechts (Standard ist false). |
| [getChildren()](#getChildren--) | Ruft untergeordnete Elemente ab |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Steuerzeichen-Eigenschaften |
### MathBorderBox(IMathElement element) {#MathBorderBox-com.aspose.slides.IMathElement-}
```
public MathBorderBox(IMathElement element)
```

Erstellt MathBorderBox-Element mit rechteckigem Rand

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Das Basiselement, auf das der Randkasten angewendet wird. Kann null sein. |

### MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Erstellt MathBorderBox-Element

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"), true, true, true, false, true, true, true, true)
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Das Basiselement, auf das der Randkasten angewendet wird. |
| hideTop | boolean | Obere Kante ausblenden |
| hideBottom | boolean | Untere Kante ausblenden |
| hideLeft | boolean | Linke Kante ausblenden |
| hideRight | boolean | Rechte Kante ausblenden |
| strikethroughHorizontal | boolean | Durchgestrichene horizontale Linie |
| strikethroughVertical | boolean | Durchgestrichene vertikale Linie |
| strikethroughBottomLeftToTopRight | boolean | Durchgestrichene diagonale Linie von unten links nach oben rechts |
| strikethroughTopLeftToBottomRight | boolean | Durchgestrichene diagonale Linie von oben links nach unten rechts |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Basisargument

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  IMathElement base = borderBox.getBase();
> ```

**Rückgabe:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public final boolean getHideTop()
```

Obere Kante ausblenden (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand der oberen Kante des Randkastens an.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**Rückgabe:**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public final void setHideTop(boolean value)
```

Obere Kante ausblenden (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand der oberen Kante des Randkastens an.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getHideBottom() {#getHideBottom--}
```
public final boolean getHideBottom()
```

Untere Kante ausblenden (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand der unteren Kante des Randkastens an.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**Rückgabe:**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public final void setHideBottom(boolean value)
```

Untere Kante ausblenden (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand der unteren Kante des Randkastens an.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getHideLeft() {#getHideLeft--}
```
public final boolean getHideLeft()
```

Linke Kante ausblenden (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand der linken Kante des Randkastens an.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**Rückgabe:**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public final void setHideLeft(boolean value)
```

Linke Kante ausblenden (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand der linken Kante des Randkastens an.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getHideRight() {#getHideRight--}
```
public final boolean getHideRight()
```

Rechte Kante ausblenden (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand der rechten Kante des Randkastens an.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**Rückgabe:**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public final void setHideRight(boolean value)
```

Rechte Kante ausblenden (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand der rechten Kante des Randkastens an.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public final boolean getStrikethroughHorizontal()
```

Durchgestrichene horizontale Linie (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand einer durchgestrichenen horizontalen Linie an.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Rückgabe:**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public final void setStrikethroughHorizontal(boolean value)
```

Durchgestrichene horizontale Linie (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand einer durchgestrichenen horizontalen Linie an.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public final boolean getStrikethroughVertical()
```

Durchgestrichene vertikale Linie (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand einer durchgestrichenen vertikalen Linie an.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**Rückgabe:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public final void setStrikethroughVertical(boolean value)
```

Durchgestrichene vertikale Linie (Standard ist false) – gibt den ausgeblendeten oder angezeigten Zustand einer durchgestrichenen vertikalen Linie an.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public final boolean getStrikethroughBottomLeftToTopRight()
```

Durchgestrichene diagonale Linie von unten links nach oben rechts (Standard ist false). Gibt den ausgeblendeten oder angezeigten Zustand einer durchgestrichenen diagonalen Linie von der unteren linken Ecke zur oberen rechten Ecke des Randkastens an.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Rückgabe:**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public final void setStrikethroughBottomLeftToTopRight(boolean value)
```

Durchgestrichene diagonale Linie von unten links nach oben rechts (Standard ist false). Gibt den ausgeblendeten oder angezeigten Zustand einer durchgestrichenen diagonalen Linie von der unteren linken Ecke zur oberen rechten Ecke des Randkastens an.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public final boolean getStrikethroughTopLeftToBottomRight()
```

Durchgestrichene diagonale Linie von oben links nach unten rechts (Standard ist false). Gibt den ausgeblendeten oder angezeigten Zustand einer durchgestrichenen diagonalen Linie von der oberen linken Ecke zur unteren rechten Ecke des Randkastens an.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Rückgabe:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public final void setStrikethroughTopLeftToBottomRight(boolean value)
```

Durchgestrichene diagonale Linie von oben links nach unten rechts (Standard ist false). Gibt den ausgeblendeten oder angezeigten Zustand einer durchgestrichenen diagonalen Linie von der oberen linken Ecke zur unteren rechten Ecke des Randkastens an.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Ruft untergeordnete Elemente ab

**Rückgabe:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Steuerzeichen-Eigenschaften

**Rückgabe:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps