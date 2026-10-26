---
title: MathBorderBox
second_title: Aspose.Slides für Android über Java-API-Referenz
description: Zeichnet einen rechteckigen oder anderen Rand um das IMathElement.
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

Zeichnet einen rechteckigen oder anderen Rand um das IMathElement.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MathBorderBox(IMathElement element)](#MathBorderBox-com.aspose.slides.IMathElement-) | Erstellt ein MathBorderBox-Element mit rechteckigem Rand |
| [MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Erstellt ein MathBorderBox-Element |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBase()](#getBase--) | Basisargument |
| [getHideTop()](#getHideTop--) | Obere Kante ausblenden (Standard ist false) – gibt an, ob die obere Kante des Randkastens ausgeblendet oder angezeigt wird. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Obere Kante ausblenden (Standard ist false) – gibt an, ob die obere Kante des Randkastens ausgeblendet oder angezeigt wird. |
| [getHideBottom()](#getHideBottom--) | Untere Kante ausblenden (Standard ist false) – gibt an, ob die untere Kante des Randkastens ausgeblendet oder angezeigt wird. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Untere Kante ausblenden (Standard ist false) – gibt an, ob die untere Kante des Randkastens ausgeblendet oder angezeigt wird. |
| [getHideLeft()](#getHideLeft--) | Linke Kante ausblenden (Standard ist false) – gibt an, ob die linke Kante des Randkastens ausgeblendet oder angezeigt wird. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Linke Kante ausblenden (Standard ist false) – gibt an, ob die linke Kante des Randkastens ausgeblendet oder angezeigt wird. |
| [getHideRight()](#getHideRight--) | Rechte Kante ausblenden (Standard ist false) – gibt an, ob die rechte Kante des Randkastens ausgeblendet oder angezeigt wird. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Rechte Kante ausblenden (Standard ist false) – gibt an, ob die rechte Kante des Randkastens ausgeblendet oder angezeigt wird. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Durchgestrichene horizontale Linie (Standard ist false) – gibt an, ob eine durchgestrichene horizontale Linie angezeigt oder ausgeblendet wird. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Durchgestrichene horizontale Linie (Standard ist false) – gibt an, ob eine durchgestrichene horizontale Linie angezeigt oder ausgeblendet wird. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Durchgestrichene vertikale Linie (Standard ist false) – gibt an, ob eine durchgestrichene vertikale Linie angezeigt oder ausgeblendet wird. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Durchgestrichene vertikale Linie (Standard ist false) – gibt an, ob eine durchgestrichene vertikale Linie angezeigt oder ausgeblendet wird. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Durchgestrichene Linie von unten links nach oben rechts (Standard ist false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Durchgestrichene Linie von unten links nach oben rechts (Standard ist false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Durchgestrichene Linie von oben links nach unten rechts (Standard ist false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Durchgestrichene Linie von oben links nach unten rechts (Standard ist false). |
| [getChildren()](#getChildren--) | Gibt Kind-Elemente zurück |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Steuerzeichen-Eigenschaften |
### MathBorderBox(IMathElement element) {#MathBorderBox-com.aspose.slides.IMathElement-}
```
public MathBorderBox(IMathElement element)
```


Erstellt ein MathBorderBox-Element mit rechteckigem Rand

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


Erstellt ein MathBorderBox-Element

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"), true, true, true, false, true, true, true, true)
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Das Basiselement, auf das der Randkasten angewendet wird |
| hideTop | boolean | Obere Kante ausblenden |
| hideBottom | boolean | Untere Kante ausblenden |
| hideLeft | boolean | Linke Kante ausblenden |
| hideRight | boolean | Rechte Kante ausblenden |
| strikethroughHorizontal | boolean | Durchgestrichene horizontale Linie |
| strikethroughVertical | boolean | Durchgestrichene vertikale Linie |
| strikethroughBottomLeftToTopRight | boolean | Durchgestrichene Linie von unten links nach oben rechts |
| strikethroughTopLeftToBottomRight | boolean | Durchgestrichene Linie von oben links nach unten rechts |

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

**Rückgabewert:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public final boolean getHideTop()
```


Obere Kante ausblenden (Standard ist false) – gibt an, ob die obere Kante des Randkastens ausgeblendet oder angezeigt wird.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**Rückgabewert:**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public final void setHideTop(boolean value)
```


Obere Kante ausblenden (Standard ist false) – gibt an, ob die obere Kante des Randkastens ausgeblendet oder angezeigt wird.

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


Untere Kante ausblenden (Standard ist false) – gibt an, ob die untere Kante des Randkastens ausgeblendet oder angezeigt wird.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**Rückgabewert:**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public final void setHideBottom(boolean value)
```


Untere Kante ausblenden (Standard ist false) – gibt an, ob die untere Kante des Randkastens ausgeblendet oder angezeigt wird.

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


Linke Kante ausblenden (Standard ist false) – gibt an, ob die linke Kante des Randkastens ausgeblendet oder angezeigt wird.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**Rückgabewert:**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public final void setHideLeft(boolean value)
```


Linke Kante ausblenden (Standard ist false) – gibt an, ob die linke Kante des Randkastens ausgeblendet oder angezeigt wird.

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


Rechte Kante ausblenden (Standard ist false) – gibt an, ob die rechte Kante des Randkastens ausgeblendet oder angezeigt wird.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**Rückgabewert:**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public final void setHideRight(boolean value)
```


Rechte Kante ausblenden (Standard ist false) – gibt an, ob die rechte Kante des Randkastens ausgeblendet oder angezeigt wird.

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


Durchgestrichene horizontale Linie (Standard ist false) – gibt an, ob eine durchgestrichene horizontale Linie angezeigt oder ausgeblendet wird.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Rückgabewert:**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public final void setStrikethroughHorizontal(boolean value)
```


Durchgestrichene horizontale Linie (Standard ist false) – gibt an, ob eine durchgestrichene horizontale Linie angezeigt oder ausgeblendet wird.

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


Durchgestrichene vertikale Linie (Standard ist false) – gibt an, ob eine durchgestrichene vertikale Linie angezeigt oder ausgeblendet wird.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**Rückgabewert:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public final void setStrikethroughVertical(boolean value)
```


Durchgestrichene vertikale Linie (Standard ist false) – gibt an, ob eine durchgestrichene vertikale Linie angezeigt oder ausgeblendet wird.

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


Durchgestrichene Linie von unten links nach oben rechts (Standard ist false). Gibt an, ob eine durchgestrichene diagonale Linie von der unteren linken Ecke zur oberen rechten Ecke des Randkastens angezeigt oder ausgeblendet wird.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Rückgabewert:**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public final void setStrikethroughBottomLeftToTopRight(boolean value)
```


Durchgestrichene Linie von unten links nach oben rechts (Standard ist false). Gibt an, ob eine durchgestrichene diagonale Linie von der unteren linken Ecke zur oberen rechten Ecke des Randkastens angezeigt oder ausgeblendet wird.

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


Durchgestrichene Linie von oben links nach unten rechts (Standard ist false). Gibt an, ob eine durchgestrichene diagonale Linie von der oberen linken Ecke zur unteren rechten Ecke des Randkastens angezeigt oder ausgeblendet wird.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Rückgabewert:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public final void setStrikethroughTopLeftToBottomRight(boolean value)
```


Durchgestrichene Linie von oben links nach unten rechts (Standard ist false). Gibt an, ob eine durchgestrichene diagonale Linie von der oberen linken Ecke zur unteren rechten Ecke des Randkastens angezeigt oder ausgeblendet wird.

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


Gibt Kind-Elemente zurück

**Rückgabewert:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Steuerzeichen-Eigenschaften

**Rückgabewert:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps