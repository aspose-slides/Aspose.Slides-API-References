---
title: MathBorderBox
second_title: Aspose.Slides for Java API Referenciája
description: Téglalap vagy más keretet rajzol az IMathElement köré.
type: docs
url: /hu/com.aspose.slides/mathborderbox/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Minden implementált interfész:**
[com.aspose.slides.IMathBorderBox](../../com.aspose.slides/imathborderbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBorderBox extends MathElementBase implements IMathBorderBox, IHasControlCharacterProperties
```

Téglalap vagy más keretet rajzol az IMathElement köré.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [MathBorderBox(IMathElement element)](#MathBorderBox-com.aspose.slides.IMathElement-) | Létrehozza a MathBorderBox elemet téglalap kerettel |
| [MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Létrehozza a MathBorderBox elemet |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getBase()](#getBase--) | Alap argumentum |
| [getHideTop()](#getHideTop--) | Felső él elrejtése (alapértelmezett hamis) - megadja a keretdoboz felső élének rejtett vagy látható állapotát. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Felső él elrejtése (alapértelmezett hamis) - megadja a keretdoboz felső élének rejtett vagy látható állapotát. |
| [getHideBottom()](#getHideBottom--) | Alsó él elrejtése (alapértelmezett hamis) - megadja a keretdoboz alsó élének rejtett vagy látható állapotát. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Alsó él elrejtése (alapértelmezett hamis) - megadja a keretdoboz alsó élének rejtett vagy látható állapotát. |
| [getHideLeft()](#getHideLeft--) | Bal él elrejtése (alapértelmezett hamis) - megadja a keretdoboz bal élének rejtett vagy látható állapotát. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Bal él elrejtése (alapértelmezett hamis) - megadja a keretdoboz bal élének rejtett vagy látható állapotát. |
| [getHideRight()](#getHideRight--) | Jobb él elrejtése (alapértelmezett hamis) - megadja a keretdoboz jobb élének rejtett vagy látható állapotát. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Jobb él elrejtése (alapértelmezett hamis) - megadja a keretdoboz jobb élének rejtett vagy látható állapotát. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Vízszintes áthúzás (alapértelmezett hamis) - megadja egy vízszintes áthúzási vonal rejtett vagy látható állapotát. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Vízszintes áthúzás (alapértelmezett hamis) - megadja egy vízszintes áthúzási vonal rejtett vagy látható állapotát. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Vertikális áthúzás (alapértelmezett hamis) - megadja egy függőleges áthúzási vonal rejtett vagy látható állapotát. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Vertikális áthúzás (alapértelmezett hamis) - megadja egy függőleges áthúzási vonal rejtett vagy látható állapotát. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Áthúzás bal alsó sarkától jobb felső sarokig (alapértelmezett hamis). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Áthúzás bal alsó sarkától jobb felső sarokig (alapértelmezett hamis). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Áthúzás bal felső sarkától jobb alsó sarokig (alapértelmezett hamis). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Áthúzás bal felső sarkától jobb alsó sarokig (alapértelmezett hamis). |
| [getChildren()](#getChildren--) | Gyermekelemek lekérése |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Vezérlő karakter tulajdonságok |
### MathBorderBox(IMathElement element) {#MathBorderBox-com.aspose.slides.IMathElement-}
```
public MathBorderBox(IMathElement element)
```

Létrehozza a MathBorderBox elemet téglalap kerettel

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Az az alap elem, amelyhez a keretdoboz alkalmazva van. Lehet null. |

### MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Létrehozza a MathBorderBox elemet

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"), true, true, true, false, true, true, true, true)
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Az alap elem, amelyhez a keretdoboz alkalmazva van |
| hideTop | boolean | Felső él elrejtése |
| hideBottom | boolean | Alsó él elrejtése |
| hideLeft | boolean | Bal él elrejtése |
| hideRight | boolean | Jobb él elrejtése |
| strikethroughHorizontal | boolean | Vízszintes áthúzás |
| strikethroughVertical | boolean | Vertikális áthúzás |
| strikethroughBottomLeftToTopRight | boolean | Áthúzás bal alsó sarkától jobb felső sarokig |
| strikethroughTopLeftToBottomRight | boolean | Áthúzás bal felső sarkától jobb alsó sarokig |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Alap argumentum

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  IMathElement base = borderBox.getBase();
> ```

**Visszatérési érték:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public final boolean getHideTop()
```

Felső él elrejtése (alapértelmezett hamis) - megadja a keretdoboz felső élének rejtett vagy látható állapotát.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**Visszatérési érték:**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public final void setHideTop(boolean value)
```

Felső él elrejtése (alapértelmezett hamis) - megadja a keretdoboz felső élének rejtett vagy látható állapotát.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public final boolean getHideBottom()
```

Alsó él elrejtése (alapértelmezett hamis) - megadja a keretdoboz alsó élének rejtett vagy látható állapotát.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**Visszatérési érték:**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public final void setHideBottom(boolean value)
```

Alsó él elrejtése (alapértelmezett hamis) - megadja a keretdoboz alsó élének rejtett vagy látható állapotát.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public final boolean getHideLeft()
```

Bal él elrejtése (alapértelmezett hamis) - megadja a keretdoboz bal élének rejtett vagy látható állapotát.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**Visszatérési érték:**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public final void setHideLeft(boolean value)
```

Bal él elrejtése (alapértelmezett hamis) - megadja a keretdoboz bal élének rejtett vagy látható állapotát.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public final boolean getHideRight()
```

Jobb él elrejtése (alapértelmezett hamis) - megadja a keretdoboz jobb élének rejtett vagy látható állapotát.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**Visszatérési érték:**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public final void setHideRight(boolean value)
```

Jobb él elrejtése (alapértelmezett hamis) - megadja a keretdoboz jobb élének rejtett vagy látható állapotát.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public final boolean getStrikethroughHorizontal()
```

Vízszintes áthúzás (alapértelmezett hamis) - megadja egy vízszintes áthúzási vonal rejtett vagy látható állapotát.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Visszatérési érték:**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public final void setStrikethroughHorizontal(boolean value)
```

Vízszintes áthúzás (alapértelmezett hamis) - megadja egy vízszintes áthúzási vonal rejtett vagy látható állapotát.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public final boolean getStrikethroughVertical()
```

Vertikális áthúzás (alapértelmezett hamis) - megadja egy függőleges áthúzási vonal rejtett vagy látható állapotát.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**Visszatérési érték:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public final void setStrikethroughVertical(boolean value)
```

Vertikális áthúzás (alapértelmezett hamis) - megadja egy függőleges áthúzási vonal rejtett vagy látható állapotát.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public final boolean getStrikethroughBottomLeftToTopRight()
```

Áthúzás bal alsó sarkától jobb felső sarokig (alapértelmezett hamis). Megadja egy áthúzott átlós vonal rejtett vagy látható állapotát a keretdoboz bal alsó sarkától jobb felső sarokig.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Visszatérési érték:**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public final void setStrikethroughBottomLeftToTopRight(boolean value)
```

Áthúzás bal alsó sarkától jobb felső sarokig (alapértelmezett hamis). Megadja egy áthúzott átlós vonal rejtett vagy látható állapotát a keretdoboz bal alsó sarkától jobb felső sarokig.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public final boolean getStrikethroughTopLeftToBottomRight()
```

Áthúzás bal felső sarkától jobb alsó sarokig (alapértelmezett hamis). Megadja egy áthúzott átlós vonal rejtett vagy látható állapotát a keretdoboz bal felső sarkától jobb alsó sarokig.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Visszatérési érték:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public final void setStrikethroughTopLeftToBottomRight(boolean value)
```

Áthúzás bal felső sarkától jobb alsó sarokig (alapértelmezett hamis). Megadja egy áthúzott átlós vonal rejtett vagy látható állapotát a keretdoboz bal felső sarkától jobb alsó sarokig.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Gyermekelemek lekérése

**Visszatérési érték:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Vezérlő karakter tulajdonságok

**Visszatérési érték:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps