---
title: MathBorderBox
second_title: Aspose.Slides för Java API-referens
description: Ritar en rektangulär eller någon annan ram runt IMathElement.
type: docs
url: /sv/com.aspose.slides/mathborderbox/
---
**Arv:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathBorderBox](../../com.aspose.slides/imathborderbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBorderBox extends MathElementBase implements IMathBorderBox, IHasControlCharacterProperties
```

Ritar en rektangulär eller någon annan ram runt IMathElement.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [MathBorderBox(IMathElement element)](#MathBorderBox-com.aspose.slides.IMathElement-) | Skapar MathBorderBox-element med rektangulär kant |
| [MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Skapar MathBorderBox-element |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getHideTop()](#getHideTop--) | Hide Top Edge (default is false) - specificerar den dolda eller visade statusen för den övre kanten av border box. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Hide Top Edge (default is false) - specificerar den dolda eller visade statusen för den övre kanten av border box. |
| [getHideBottom()](#getHideBottom--) | Hide Bottom Edge (default is false) - specificerar den dolda eller visade statusen för den nedre kanten av border box. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Hide Bottom Edge (default is false) - specificerar den dolda eller visade statusen för den nedre kanten av border box. |
| [getHideLeft()](#getHideLeft--) | Hide Left Edge (default is false) - specificerar den dolda eller visade statusen för den vänstra kanten av border box. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Hide Left Edge (default is false) - specificerar den dolda eller visade statusen för den vänstra kanten av border box. |
| [getHideRight()](#getHideRight--) | Hide Right Edge (default is false) - specificerar den dolda eller visade statusen för den högra kanten av border box. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Hide Right Edge (default is false) - specificerar den dolda eller visade statusen för den högra kanten av border box. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Strikethrough Horizontal (default is false) - specificerar den dolda eller visade statusen för en horisontell genomstrykning. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Strikethrough Horizontal (default is false) - specificerar den dolda eller visade statusen för en horisontell genomstrykning. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Strikethrough Vertical (default is false) - specificerar den dolda eller visade statusen för en vertikal genomstrykning. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Strikethrough Vertical (default is false) - specificerar den dolda eller visade statusen för en vertikal genomstrykning. |
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

Skapar MathBorderBox-element med rektangulär kant

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Basiselementet som border box appliceras på. Kan vara null. |

### MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Skapar MathBorderBox-element

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"), true, true, true, false, true, true, true, true)
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Basiselementet som border box appliceras på |
| hideTop | boolean | Hide Top Edge |
| hideBottom | boolean | Hide Bottom Edge |
| hideLeft | boolean | Hide Left Edge |
| hideRight | boolean | Hide Right Edge |
| strikethroughHorizontal | boolean | Strikethrough Horizontal |
| strikethroughVertical | boolean | Strikethrough Vertical |
| strikethroughBottomLeftToTopRight | boolean | Strikethrough Bottom-Left to Top-Right |
| strikethroughTopLeftToBottomRight | boolean | Strikethrough Top-Left to Bottom-Right |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Basargument

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  IMathElement base = borderBox.getBase();
> ```

**Returnerar:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public final boolean getHideTop()
```

Hide Top Edge (standard är falskt) - specificerar den dolda eller visade statusen för den övre kanten av border box.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**Returnerar:**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public final void setHideTop(boolean value)
```

Hide Top Edge (standard är falskt) - specificerar den dolda eller visade statusen för den övre kanten av border box.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public final boolean getHideBottom()
```

Hide Bottom Edge (standard är falskt) - specificerar den dolda eller visade statusen för den nedre kanten av border box.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**Returnerar:**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public final void setHideBottom(boolean value)
```

Hide Bottom Edge (standard är falskt) - specificerar den dolda eller visade statusen för den nedre kanten av border box.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public final boolean getHideLeft()
```

Hide Left Edge (standard är falskt) - specificerar den dolda eller visade statusen för den vänstra kanten av border box.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**Returnerar:**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public final void setHideLeft(boolean value)
```

Hide Left Edge (standard är falskt) - specificerar den dolda eller visade statusen för den vänstra kanten av border box.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public final boolean getHideRight()
```

Hide Right Edge (standard är falskt) - specificerar den dolda eller visade statusen för den högra kanten av border box.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**Returnerar:**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public final void setHideRight(boolean value)
```

Hide Right Edge (standard är falskt) - specificerar den dolda eller visade statusen för den högra kanten av border box.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public final boolean getStrikethroughHorizontal()
```

Strikethrough Horizontal (standard är falskt) - specificerar den dolda eller visade statusen för en horisontell genomstrykning.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Returnerar:**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public final void setStrikethroughHorizontal(boolean value)
```

Strikethrough Horizontal (standard är falskt) - specificerar den dolda eller visade statusen för en horisontell genomstrykning.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public final boolean getStrikethroughVertical()
```

Strikethrough Vertical (standard är falskt) - specificerar den dolda eller visade statusen för en vertikal genomstrykning.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**Returnerar:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public final void setStrikethroughVertical(boolean value)
```

Strikethrough Vertical (standard är falskt) - specificerar den dolda eller visade statusen för en vertikal genomstrykning.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public final boolean getStrikethroughBottomLeftToTopRight()
```

Strikethrough Bottom-Left to Top-Right (standard är falskt). Specificerar den dolda eller visade statusen för en diagonal genomstrykning från nedre vänstra hörnet till övre högra hörnet av border box.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Returnerar:**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public final void setStrikethroughBottomLeftToTopRight(boolean value)
```

Strikethrough Bottom-Left to Top-Right (standard är falskt). Specificerar den dolda eller visade statusen för en diagonal genomstrykning från nedre vänstra hörnet till övre högra hörnet av border box.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public final boolean getStrikethroughTopLeftToBottomRight()
```

Strikethrough Top-Left to Bottom-Right (standard är falskt). Specificerar den dolda eller visade statusen för en diagonal genomstrykning från övre vänstra hörnet till nedre högra hörnet av border box.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Returnerar:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public final void setStrikethroughTopLeftToBottomRight(boolean value)
```

Strikethrough Top-Left to Bottom-Right (standard är falskt). Specificerar den dolda eller visade statusen för en diagonal genomstrykning från övre vänstra hörnet till nedre högra hörnet av border box.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Hämta underordnade element

**Returnerar:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Control Character Properties

**Returnerar:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps