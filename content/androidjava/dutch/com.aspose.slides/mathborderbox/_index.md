---
title: MathBorderBox
second_title: Aspose.Slides voor Android via Java API-referentie
description: Tekent een rechthoekige of een andere rand rond het IMathElement.
type: docs
url: /nl/com.aspose.slides/mathborderbox/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathBorderBox](../../com.aspose.slides/imathborderbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBorderBox extends MathElementBase implements IMathBorderBox, IHasControlCharacterProperties
```

Tekent een rechthoekige of een andere rand om het IMathElement.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [MathBorderBox(IMathElement element)](#MathBorderBox-com.aspose.slides.IMathElement-) | Creëert MathBorderBox-element met rechthoekige rand |
| [MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Creëert MathBorderBox-element |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getHideTop()](#getHideTop--) | Hide Top Edge (default is false) - specifies the hidden or shown state of the top edge of border box. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Hide Top Edge (default is false) - specifies the hidden or shown state of the top edge of border box. |
| [getHideBottom()](#getHideBottom--) | Hide Bottom Edge (default is false) - specifies the hidden or shown state of the bottom edge of border box. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Hide Bottom Edge (default is false) - specifies the hidden or shown state of the bottom edge of border box. |
| [getHideLeft()](#getHideLeft--) | Hide Left Edge (default is false) - specifies the hidden or shown state of the left edge of border box. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Hide Left Edge (default is false) - specifies the hidden or shown state of the left edge of border box. |
| [getHideRight()](#getHideRight--) | Hide Right Edge (default is false) - specifies the hidden or shown state of the right edge of border box. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Hide Right Edge (default is false) - specifies the hidden or shown state of the right edge of border box. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Strikethrough Horizontal (default is false) - specifies the hidden or shown state of a strikethrough horizontal line. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Strikethrough Horizontal (default is false) - specifies the hidden or shown state of a strikethrough horizontal line. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Strikethrough Vertical (default is false) - specifies the hidden or shown state of a strikethrough vertical line. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Strikethrough Vertical (default is false) - specifies the hidden or shown state of a strikethrough vertical line. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Strikethrough Bottom-Left to Top-Right (default is false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Strikethrough Bottom-Left to Top-Right (default is false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Strikethrough Top-Left to Bottom-Right (default is false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Strikethrough Top-Left to Bottom-Right (default is false). |
| [getChildren()](#getChildren--) | Get children elements |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
### MathBorderBox(IMathElement element) {#MathBorderBox-com.aspose.slides.IMathElement-}
```
public MathBorderBox(IMathElement element)
```


Creëert MathBorderBox-element met rechthoekige rand

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Het basiselement waaraan de randbox wordt toegepast. Kan null zijn. |

### MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


Creëert MathBorderBox-element

--------------------

> ```
> Voorbeeld:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"), true, true, true, false, true, true, true, true)
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Het basiselement waaraan de randbox wordt toegepast |
| hideTop | boolean | Verberg bovenrand |
| hideBottom | boolean | Verberg onderrand |
| hideLeft | boolean | Verberg linkerrand |
| hideRight | boolean | Verberg rechterrand |
| strikethroughHorizontal | boolean | Doorhalen horizontaal |
| strikethroughVertical | boolean | Doorhalen verticaal |
| strikethroughBottomLeftToTopRight | boolean | Doorhalen van onder links naar boven rechts |
| strikethroughTopLeftToBottomRight | boolean | Doorhalen van boven links naar onder rechts |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Basisargument

--------------------

> ```
> Voorbeeld:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  IMathElement base = borderBox.getBase();
> ```

**Retourwaarde:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public final boolean getHideTop()
```


Verberg bovenrand (default is false) - geeft de verborgen of weergegeven staat van de bovenrand van de randbox aan.

--------------------

> ```
> Voorbeeld:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**Retourwaarde:**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public final void setHideTop(boolean value)
```


Verberg bovenrand (default is false) - geeft de verborgen of weergegeven staat van de bovenrand van de randbox aan.

--------------------

> ```
> Voorbeeld:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public final boolean getHideBottom()
```


Verberg onderrand (default is false) - geeft de verborgen of weergegeven staat van de onderrand van de randbox aan.

--------------------

> ```
> Voorbeeld:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**Retourwaarde:**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public final void setHideBottom(boolean value)
```


Verberg onderrand (default is false) - geeft de verborgen of weergegeven staat van de onderrand van de randbox aan.

--------------------

> ```
> Voorbeeld:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public final boolean getHideLeft()
```


Verberg linkerrand (default is false) - geeft de verborgen of weergegeven staat van de linkerrand van de randbox aan.

--------------------

> ```
> Voorbeeld:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**Retourwaarde:**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public final void setHideLeft(boolean value)
```


Verberg linkerrand (default is false) - geeft de verborgen of weergegeven staat van de linkerrand van de randbox aan.

--------------------

> ```
> Voorbeeld:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public final boolean getHideRight()
```


Verberg rechterrand (default is false) - geeft de verborgen of weergegeven staat van de rechterrand van de randbox aan.

--------------------

> ```
> Voorbeeld:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**Retourwaarde:**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public final void setHideRight(boolean value)
```


Verberg rechterrand (default is false) - geeft de verborgen of weergegeven staat van de rechterrand van de randbox aan.

--------------------

> ```
> Voorbeeld:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public final boolean getStrikethroughHorizontal()
```


Doorhalen horizontaal (default is false) - geeft de verborgen of weergegeven staat van een horizontale doorhaallijn aan.

--------------------

> ```
> Voorbeeld:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Retourwaarde:**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public final void setStrikethroughHorizontal(boolean value)
```


Doorhalen horizontaal (default is false) - geeft de verborgen of weergegeven staat van een horizontale doorhaallijn aan.

--------------------

> ```
> Voorbeeld:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public final boolean getStrikethroughVertical()
```


Doorhalen verticaal (default is false) - geeft de verborgen of weergegeven staat van een verticale doorhaallijn aan.

--------------------

> ```
> Voorbeeld:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**Retourwaarde:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public final void setStrikethroughVertical(boolean value)
```


Doorhalen verticaal (default is false) - geeft de verborgen of weergegeven staat van een verticale doorhaallijn aan.

--------------------

> ```
> Voorbeeld:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public final boolean getStrikethroughBottomLeftToTopRight()
```


Doorhalen van onder links naar boven rechts (default is false). Geeft de verborgen of weergegeven staat van een diagonale doorhaallijn van de onder-linkerhoek naar de boven-rechterhoek van de randbox aan.

--------------------

> ```
> Voorbeeld:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
```

**Retourwaarde:**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public final void setStrikethroughBottomLeftToTopRight(boolean value)
```


Doorhalen van onder links naar boven rechts (default is false). Geeft de verborgen of weergegeven staat van een diagonale doorhaallijn van de onder-linkerhoek naar de boven-rechterhoek van de randbox aan.

--------------------

> ```
> Voorbeeld:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public final boolean getStrikethroughTopLeftToBottomRight()
```


Doorhalen van boven links naar onder rechts (default is false). Geeft de verborgen of weergegeven staat van een diagonale doorhaallijn van de boven-linkerhoek naar de onder-rechterhoek van de randbox aan.

--------------------

> ```
> Voorbeeld:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Retourwaarde:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public final void setStrikethroughTopLeftToBottomRight(boolean value)
```


Doorhalen van boven links naar onder rechts (default is false). Geeft de verborgen of weergegeven staat van een diagonale doorhaallijn van de boven-linkerhoek naar de onder-rechterhoek van de randbox aan.

--------------------

> ```
> Voorbeeld:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Haal kindelementen op

**Retourwaarde:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Control Character-eigenschappen

**Retourwaarde:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps