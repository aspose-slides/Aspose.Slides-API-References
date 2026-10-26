---
title: IMathBorderBox
second_title: Aspose.Slides Androidhoz a Java API-referencián keresztül
description: Téglalap vagy más típusú keretet rajzol az IMathElement köré.
type: docs
url: /hu/com.aspose.slides/imathborderbox/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBorderBox extends IMathElement
```

Egy téglalap vagy más típusú keretet rajzol az IMathElement köré.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```
## Metódusok

| Módszer | Leírás |
| --- | --- |
| [getBase()](#getBase--) | Alap argumentum |
| [getHideTop()](#getHideTop--) | Felső él elrejtése (alapértelmezett érték hamis) – meghatározza a keretdoboz felső élének rejtett vagy látható állapotát. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Felső él elrejtése (alapértelmezett érték hamis) – meghatározza a keretdoboz felső élének rejtett vagy látható állapotát. |
| [getHideBottom()](#getHideBottom--) | Alsó él elrejtése (alapértelmezett érték hamis) – meghatározza a keretdoboz alsó élének rejtett vagy látható állapotát. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Alsó él elrejtése (alapértelmezett érték hamis) – meghatározza a keretdoboz alsó élének rejtett vagy látható állapotát. |
| [getHideLeft()](#getHideLeft--) | Bal él elrejtése (alapértelmezett érték hamis) – meghatározza a keretdoboz bal élének rejtett vagy látható állapotát. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Bal él elrejtése (alapértelmezett érték hamis) – meghatározza a keretdoboz bal élének rejtett vagy látható állapotát. |
| [getHideRight()](#getHideRight--) | Jobb él elrejtése (alapértelmezett érték hamis) – meghatározza a keretdoboz jobb élének rejtett vagy látható állapotát. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Jobb él elrejtése (alapértelmezett érték hamis) – meghatározza a keretdoboz jobb élének rejtett vagy látható állapotát. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Vízszintes áthúzás (alapértelmezett érték hamis) – meghatározza egy vízszintes áthúzási vonal rejtett vagy látható állapotát. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Vízszintes áthúzás (alapértelmezett érték hamis) – meghatározza egy vízszintes áthúzási vonal rejtett vagy látható állapotát. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Függőleges áthúzás (alapértelmezett érték hamis) – meghatározza egy függőleges áthúzási vonal rejtett vagy látható állapotát. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Függőleges áthúzás (alapértelmezett érték hamis) – meghatározza egy függőleges áthúzási vonal rejtett vagy látható állapotát. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Bal alsó saroktól jobb felsőig áthúzás (alapértelmezett érték hamis). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Bal alsó saroktól jobb felsőig áthúzás (alapértelmezett érték hamis). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Bal felső saroktól jobb alsóig áthúzás (alapértelmezett érték hamis). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Bal felső saroktól jobb alsóig áthúzás (alapértelmezett érték hamis). |

### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Alap argumentum

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  IMathElement base = borderBox.getBase();
> ```


**Visszatér:**
[IMathElement](../../com.aspose.slides/imathelement)

### getHideTop() {#getHideTop--}
```
public abstract boolean getHideTop()
```

Felső él elrejtése (alapértelmezett érték hamis) – meghatározza a keretdoboz felső élének rejtett vagy látható állapotát.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**Visszatér:**
boolean

### setHideTop(boolean value) {#setHideTop-boolean-}
```
public abstract void setHideTop(boolean value)
```

Felső él elrejtése (alapértelmezett érték hamis) – meghatározza a keretdoboz felső élének rejtett vagy látható állapotát.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public abstract boolean getHideBottom()
```

Alsó él elrejtése (alapértelmezett érték hamis) – meghatározza a keretdoboz alsó élének rejtett vagy látható állapotát.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**Visszatér:**
boolean

### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public abstract void setHideBottom(boolean value)
```

Alsó él elrejtése (alapértelmezett érték hamis) – meghatározza a keretdoboz alsó élének rejtett vagy látható állapotát.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public abstract boolean getHideLeft()
```

Bal él elrejtése (alapértelmezett érték hamis) – meghatározza a keretdoboz bal élének rejtett vagy látható állapotát.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**Visszatér:**
boolean

### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public abstract void setHideLeft(boolean value)
```

Bal él elrejtése (alapértelmezett érték hamis) – meghatározza a keretdoboz bal élének rejtett vagy látható állapotát.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public abstract boolean getHideRight()
```

Jobb él elrejtése (alapértelmezett érték hamis) – meghatározza a keretdoboz jobb élének rejtett vagy látható állapotát.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**Visszatér:**
boolean

### setHideRight(boolean value) {#setHideRight-boolean-}
```
public abstract void setHideRight(boolean value)
```

Jobb él elrejtése (alapértelmezett érték hamis) – meghatározza a keretdoboz jobb élének rejtett vagy látható állapotát.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public abstract boolean getStrikethroughHorizontal()
```

Vízszintes áthúzás (alapértelmezett érték hamis) – meghatározza egy vízszintes áthúzási vonal rejtett vagy látható állapotát.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Visszatér:**
boolean

### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public abstract void setStrikethroughHorizontal(boolean value)
```

Vízszintes áthúzás (alapértelmezett érték hamis) – meghatározza egy vízszintes áthúzási vonal rejtett vagy látható állapotát.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public abstract boolean getStrikethroughVertical()
```

Függőleges áthúzás (alapértelmezett érték hamis) – meghatározza egy függőleges áthúzási vonal rejtett vagy látható állapotát.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**Visszatér:**
boolean

### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public abstract void setStrikethroughVertical(boolean value)
```

Függőleges áthúzás (alapértelmezett érték hamis) – meghatározza egy függőleges áthúzási vonal rejtett vagy látható állapotát.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public abstract boolean getStrikethroughBottomLeftToTopRight()
```

Bal alsó saroktól jobb felsőig áthúzás (alapértelmezett érték hamis). Meghatározza egy átlós áthúzási vonal rejtett vagy látható állapotát a bal alsó saroktól a jobb felső sarokig a keretdobozban.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Visszatér:**
boolean

### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public abstract void setStrikethroughBottomLeftToTopRight(boolean value)
```

Bal alsó saroktól jobb felsőig áthúzás (alapértelmezett érték hamis). Meghatározza egy átlós áthúzási vonal rejtett vagy látható állapotát a bal alsó saroktól a jobb felső sarokig a keretdobozban.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public abstract boolean getStrikethroughTopLeftToBottomRight()
```

Bal felső saroktól jobb alsóig áthúzás (alapértelmezett érték hamis). Meghatározza egy átlós áthúzási vonal rejtett vagy látható állapotát a bal felső saroktól a jobb alsó sarokig a keretdobozban.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Visszatér:**
boolean

### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public abstract void setStrikethroughTopLeftToBottomRight(boolean value)
```

Bal felső saroktól jobb alsóig áthúzás (alapértelmezett érték hamis). Meghatározza egy átlós áthúzási vonal rejtett vagy látható állapotát a bal felső saroktól a jobb alsó sarokig a keretdobozban.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |