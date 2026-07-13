---
title: MathBorderBox
second_title: Aspose.Slides för Android via Java API-referens
description: Ritar en rektangulär eller någon annan kant runt IMathElement.
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

Ritar en rektangulär eller någon annan kant runt IMathElement.

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
| [getBase()](#getBase--) | Basargument |
| [getHideTop()](#getHideTop--) | Dölj övre kant (standard är falskt) - specificerar det dolda eller visade tillståndet för den övre kanten av kantboxen. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Dölj övre kant (standard är falskt) - specificerar det dolda eller visade tillståndet för den övre kanten av kantboxen. |
| [getHideBottom()](#getHideBottom--) | Dölj nedre kant (standard är falskt) - specificerar det dolda eller visade tillståndet för den nedre kanten av kantboxen. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Dölj nedre kant (standard är falskt) - specificerar det dolda eller visade tillståndet för den nedre kanten av kantboxen. |
| [getHideLeft()](#getHideLeft--) | Dölj vänsterkant (standard är falskt) - specificerar det dolda eller visade tillståndet för den vänstra kanten av kantboxen. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Dölj vänsterkant (standard är falskt) - specificerar det dolda eller visade tillståndet för den vänstra kanten av kantboxen. |
| [getHideRight()](#getHideRight--) | Dölj högerkant (standard är falskt) - specificerar det dolda eller visade tillståndet för den högra kanten av kantboxen. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Dölj högerkant (standard är falskt) - specificerar det dolda eller visade tillståndet för den högra kanten av kantboxen. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Genomstruken horisontell (standard är falskt) - specificerar det dolda eller visade tillståndet för en genomstruken horisontell linje. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Genomstruken horisontell (standard är falskt) - specificerar det dolda eller visade tillståndet för en genomstruken horisontell linje. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Genomstruken vertikal (standard är falskt) - specificerar det dolda eller visade tillståndet för en genomstruken vertikal linje. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Genomstruken vertikal (standard är falskt) - specificerar det dolda eller visade tillståndet för en genomstruken vertikal linje. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Genomstruken nedre vänster till övre högra (standard är falskt). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Genomstruken nedre vänster till övre högra (standard är falskt). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Genomstruken övre vänster till nedre högra (standard är falskt). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Genomstruken övre vänster till nedre högra (standard är falskt). |
| [getChildren()](#getChildren--) | Hämta barnelement |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Kontrollteckenegenskaper |
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
| element | [IMathElement](../../com.aspose.slides/imathelement) | Baselementet som kantboxen appliceras på. Kan vara null. |

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
| element | [IMathElement](../../com.aspose.slides/imathelement) | Baselementet som kantboxen appliceras på |
| hideTop | boolean | Dölj övre kant |
| hideBottom | boolean | Dölj nedre kant |
| hideLeft | boolean | Dölj vänsterkant |
| hideRight | boolean | Dölj högerkant |
| strikethroughHorizontal | boolean | Genomstruken horisontell |
| strikethroughVertical | boolean | Genomstruken vertikal |
| strikethroughBottomLeftToTopRight | boolean | Genomstruken nedre vänster till övre högra |
| strikethroughTopLeftToBottomRight | boolean | Genomstruken övre vänster till nedre högra |

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


Dölj övre kant (standard är falskt) - specificerar det dolda eller visade tillståndet för den övre kanten av kantboxen.

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


Dölj övre kant (standard är falskt) - specificerar det dolda eller visade tillståndet för den övre kanten av kantboxen.

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


Dölj nedre kant (standard är falskt) - specificerar det dolda eller visade tillståndet för den nedre kanten av kantboxen.

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


Dölj nedre kant (standard är falskt) - specificerar det dolda eller visade tillståndet för den nedre kanten av kantboxen.

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


Dölj vänsterkant (standard är falskt) - specificerar det dolda eller visade tillståndet för den vänstra kanten av kantboxen.

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


Dölj vänsterkant (standard är falskt) - specificerar det dolda eller visade tillståndet för den vänstra kanten av kantboxen.

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


Dölj högerkant (standard är falskt) - specificerar det dolda eller visade tillståndet för den högra kanten av kantboxen.

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


Dölj högerkant (standard är falskt) - specificerar det dolda eller visade tillståndet för den högra kanten av kantboxen.

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


Genomstruken horisontell (standard är falskt) - specificerar det dolda eller visade tillståndet för en genomstruken horisontell linje.

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


Genomstruken horisontell (standard är falskt) - specificerar det dolda eller visade tillståndet för en genomstruken horisontell linje.

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


Genomstruken vertikal (standard är falskt) - specificerar det dolda eller visade tillståndet för en genomstruken vertikal linje.

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


Genomstruken vertikal (standard är falskt) - specificerar det dolda eller visade tillståndet för en genomstruken vertikal linje.

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


Genomstruken nedre vänster till övre högra (standard är falskt). Specificerar det dolda eller visade tillståndet för en genomstruken diagonal linje från nedre vänstra hörnet till övre högra hörnet av kantboxen.

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


Genomstruken nedre vänster till övre högra (standard är falskt). Specificerar det dolda eller visade tillståndet för en genomstruken diagonal linje från nedre vänstra hörnet till övre högra hörnet av kantboxen.

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


Genomstruken övre vänster till nedre högra (standard är falskt). Specificerar det dolda eller visade tillståndet för en genomstruken diagonal linje från övre vänstra hörnet till nedre högra hörnet av kantboxen.

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


Genomstruken övre vänster till nedre högra (standard är falskt). Specificerar det dolda eller visade tillståndet för en genomstruken diagonal linje från övre vänstra hörnet till nedre högra hörnet av kantboxen.

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


Hämta barnelement

**Returnerar:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Kontrollteckenegenskaper

**Returnerar:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps