---
title: IMathBorderBox
second_title: Aspose.Slides för Java API-referens
description: Ritar en rektangulär eller annan ram runt IMathElement.
type: docs
url: /sv/com.aspose.slides/imathborderbox/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBorderBox extends IMathElement
```

Ritar en rektangulär eller annan ram runt IMathElement.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBase()](#getBase--) | Basargument |
| [getHideTop()](#getHideTop--) | Hide Top Edge (standard är falskt) - anger det dolda eller visade tillståndet för den övre kanten av border box. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Hide Top Edge (standard är falskt) - anger det dolda eller visade tillståndet för den övre kanten av border box. |
| [getHideBottom()](#getHideBottom--) | Hide Bottom Edge (standard är falskt) - anger det dolda eller visade tillståndet för den nedre kanten av border box. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Hide Bottom Edge (standard är falskt) - anger det dolda eller visade tillståndet för den nedre kanten av border box. |
| [getHideLeft()](#getHideLeft--) | Hide Left Edge (standard är falskt) - anger det dolda eller visade tillståndet för den vänstra kanten av border box. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Hide Left Edge (standard är falskt) - anger det dolda eller visade tillståndet för den vänstra kanten av border box. |
| [getHideRight()](#getHideRight--) | Hide Right Edge (standard är falskt) - anger det dolda eller visade tillståndet för den högra kanten av border box. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Hide Right Edge (standard är falskt) - anger det dolda eller visade tillståndet för den högra kanten av border box. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Strikethrough Horizontal (standard är falskt) - anger det dolda eller visade tillståndet för en genomstruken horisontell linje. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Strikethrough Horizontal (standard är falskt) - anger det dolda eller visade tillståndet för en genomstruken horisontell linje. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Strikethrough Vertical (standard är falskt) - anger det dolda eller visade tillståndet för en genomstruken vertikal linje. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Strikethrough Vertical (standard är falskt) - anger det dolda eller visade tillståndet för en genomstruken vertikal linje. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Strikethrough Bottom-Left to Top-Right (standard är falskt). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Strikethrough Bottom-Left to Top-Right (standard är falskt). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Strikethrough Top-Left to Bottom-Right (standard är falskt). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Strikethrough Top-Left to Bottom-Right (standard är falskt). |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Basargument

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  IMathElement base = borderBox.getBase();
> ```

**Returnerar:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public abstract boolean getHideTop()
```

Hide Top Edge (standard är falskt) - anger det dolda eller visade tillståndet för den övre kanten av border box.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```


**Returnerar:**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public abstract void setHideTop(boolean value)
```

Hide Top Edge (standard är falskt) - anger det dolda eller visade tillståndet för den övre kanten av border box.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public abstract boolean getHideBottom()
```

Hide Bottom Edge (standard är falskt) - anger det dolda eller visade tillståndet för den nedre kanten av border box.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**Returnerar:**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public abstract void setHideBottom(boolean value)
```

Hide Bottom Edge (standard är falskt) - anger det dolda eller visade tillståndet för den nedre kanten av border box.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public abstract boolean getHideLeft()
```

Hide Left Edge (standard är falskt) - anger det dolda eller visade tillståndet för den vänstra kanten av border box.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**Returnerar:**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public abstract void setHideLeft(boolean value)
```

Hide Left Edge (standard är falskt) - anger det dolda eller visade tillståndet för den vänstra kanten av border box.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public abstract boolean getHideRight()
```

Hide Right Edge (standard är falskt) - anger det dolda eller visade tillståndet för den högra kanten av border box.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**Returnerar:**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public abstract void setHideRight(boolean value)
```

Hide Right Edge (standard är falskt) - anger det dolda eller visade tillståndet för den högra kanten av border box.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public abstract boolean getStrikethroughHorizontal()
```

Strikethrough Horizontal (standard är falskt) - anger det dolda eller visade tillståndet för en genomstruken horisontell linje.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Returnerar:**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public abstract void setStrikethroughHorizontal(boolean value)
```

Strikethrough Horizontal (standard är falskt) - anger det dolda eller visade tillståndet för en genomstruken horisontell linje.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public abstract boolean getStrikethroughVertical()
```

Strikethrough Vertical (standard är falskt) - anger det dolda eller visade tillståndet för en genomstruken vertikal linje.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**Returnerar:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public abstract void setStrikethroughVertical(boolean value)
```

Strikethrough Vertical (standard är falskt) - anger det dolda eller visade tillståndet för en genomstruken vertikal linje.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public abstract boolean getStrikethroughBottomLeftToTopRight()
```

Strikethrough Bottom-Left to Top-Right (standard är falskt). Anger det dolda eller visade tillståndet för en genomstruken diagonal linje från den nedre vänstra hörnet till den övre högra hörnet av border box.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Returnerar:**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public abstract void setStrikethroughBottomLeftToTopRight(boolean value)
```

Strikethrough Bottom-Left to Top-Right (standard är falskt). Anger det dolda eller visade tillståndet för en genomstruken diagonal linje från den nedre vänstra hörnet till den övre högra hörnet av border box.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public abstract boolean getStrikethroughTopLeftToBottomRight()
```

Strikethrough Top-Left to Bottom-Right (standard är falskt). Anger det dolda eller visade tillståndet för en genomstruken diagonal linje från den övre vänstra hörnet till den nedre högra hörnet av border box.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Returnerar:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public abstract void setStrikethroughTopLeftToBottomRight(boolean value)
```

Strikethrough Top-Left to Bottom-Right (standard är falskt). Anger det dolda eller visade tillståndet för en genomstruken diagonal linje från den övre vänstra hörnet till den nedre högra hörnet av border box.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |