---
title: IMathBorderBox
second_title: Aspose.Slides för Android via Java API-referens
description: Ritar en rektangulär eller någon annan ram runt IMathElement.
type: docs
url: /sv/com.aspose.slides/imathborderbox/
---
**All Implemented Interfaces:**
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
| [getHideTop()](#getHideTop--) | Dölj övre kanten (standardvärdet är false) - anger det dolda eller visade tillståndet för den övre kanten av ramrutan. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Dölj övre kanten (standardvärdet är false) - anger det dolda eller visade tillståndet för den övre kanten av ramrutan. |
| [getHideBottom()](#getHideBottom--) | Dölj nedre kanten (standardvärdet är false) - anger det dolda eller visade tillståndet för den nedre kanten av ramrutan. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Dölj nedre kanten (standardvärdet är false) - anger det dolda eller visade tillståndet för den nedre kanten av ramrutan. |
| [getHideLeft()](#getHideLeft--) | Dölj vänstra kanten (standardvärdet är false) - anger det dolda eller visade tillståndet för den vänstra kanten av ramrutan. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Dölj vänstra kanten (standardvärdet är false) - anger det dolda eller visade tillståndet för den vänstra kanten av ramrutan. |
| [getHideRight()](#getHideRight--) | Dölj högra kanten (standardvärdet är false) - anger det dolda eller visade tillståndet för den högra kanten av ramrutan. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Dölj högra kanten (standardvärdet är false) - anger det dolda eller visade tillståndet för den högra kanten av ramrutan. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Genomstrykning horisontell (standardvärdet är false) - anger det dolda eller visade tillståndet för en genomstrykning horisontell linje. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Genomstrykning horisontell (standardvärdet är false) - anger det dolda eller visade tillståndet för en genomstrykning horisontell linje. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Genomstrykning vertikal (standardvärdet är false) - anger det dolda eller visade tillståndet för en genomstrykning vertikal linje. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Genomstrykning vertikal (standardvärdet är false) - anger det dolda eller visade tillståndet för en genomstrykning vertikal linje. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Genomstrykning nedre vänstra till övre högra (standardvärdet är false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Genomstrykning nedre vänstra till övre högra (standardvärdet är false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Genomstrykning övre vänstra till nedre högra (standardvärdet är false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Genomstrykning övre vänstra till nedre högra (standardvärdet är false). |

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

Dölj övre kanten (standardvärdet är false) - anger det dolda eller visade tillståndet för den övre kanten av ramrutan.

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

Dölj övre kanten (standardvärdet är false) - anger det dolda eller visade tillståndet för den övre kanten av ramrutan.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public abstract boolean getHideBottom()
```

Dölj nedre kanten (standardvärdet är false) - anger det dolda eller visade tillståndet för den nedre kanten av ramrutan.

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

Dölj nedre kanten (standardvärdet är false) - anger det dolda eller visade tillståndet för den nedre kanten av ramrutan.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public abstract boolean getHideLeft()
```

Dölj vänstra kanten (standardvärdet är false) - anger det dolda eller visade tillståndet för den vänstra kanten av ramrutan.

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

Dölj vänstra kanten (standardvärdet är false) - anger det dolda eller visade tillståndet för den vänstra kanten av ramrutan.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public abstract boolean getHideRight()
```

Dölj högra kanten (standardvärdet är false) - anger det dolda eller visade tillståndet för den högra kanten av ramrutan.

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

Dölj högra kanten (standardvärdet är false) - anger det dolda eller visade tillståndet för den högra kanten av ramrutan.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public abstract boolean getStrikethroughHorizontal()
```

Genomstrykning horisontell (standardvärdet är false) - anger det dolda eller visade tillståndet för en genomstrykning horisontell linje.

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

Genomstrykning horisontell (standardvärdet är false) - anger det dolda eller visade tillståndet för en genomstrykning horisontell linje.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public abstract boolean getStrikethroughVertical()
```

Genomstrykning vertikal (standardvärdet är false) - anger det dolda eller visade tillståndet för en genomstrykning vertikal linje.

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

Genomstrykning vertikal (standardvärdet är false) - anger det dolda eller visade tillståndet för en genomstrykning vertikal linje.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public abstract boolean getStrikethroughBottomLeftToTopRight()
```

Genomstrykning nedre vänstra till övre högra (standardvärdet är false). Anger det dolda eller visade tillståndet för en genomstrykning diagonal linje från nedre vänstra hörnet till övre högra hörnet av ramrutan.

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

Genomstrykning nedre vänstra till övre högra (standardvärdet är false). Anger det dolda eller visade tillståndet för en genomstrykning diagonal linje från nedre vänstra hörnet till övre högra hörnet av ramrutan.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public abstract boolean getStrikethroughTopLeftToBottomRight()
```

Genomstrykning övre vänstra till nedre högra (standardvärdet är false). Anger det dolda eller visade tillståndet för en genomstrykning diagonal linje från övre vänstra hörnet till nedre högra hörnet av ramrutan.

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

Genomstrykning övre vänstra till nedre högra (standardvärdet är false). Anger det dolda eller visade tillståndet för en genomstrykning diagonal linje från övre vänstra hörnet till nedre högra hörnet av ramrutan.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |