---
title: MathBorderBox
second_title: Aspose.Slides for Android Java API-referencia
description: Téglalap vagy más keretet rajzol az IMathElement köré.
type: docs
url: /hu/com.aspose.slides/mathborderbox/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Minden megvalósított interfész:**
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
| [MathBorderBox(IMathElement element)](#MathBorderBox-com.aspose.slides.IMathElement-) | Létrehozza a MathBorderBox elemet téglalap alakú kerettel |
| [MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Létrehozza a MathBorderBox elemet |
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getBase()](#getBase--) | Alap argumentum |
| [getHideTop()](#getHideTop--) | Elrejti a felső élt (alapértelmezett érték false) – meghatározza a keret doboz felső élének rejtett vagy látható állapotát. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Elrejti a felső élt (alapértelmezett érték false) – meghatározza a keret doboz felső élének rejtett vagy látható állapotát. |
| [getHideBottom()](#getHideBottom--) | Elrejti az alsó élt (alapértelmezett érték false) – meghatározza a keret doboz alsó élének rejtett vagy látható állapotát. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Elrejti az alsó élt (alapértelmezett érték false) – meghatározza a keret doboz alsó élének rejtett vagy látható állapotát. |
| [getHideLeft()](#getHideLeft--) | Elrejti a bal oldali élt (alapértelmezett érték false) – meghatározza a keret doboz bal élének rejtett vagy látható állapotát. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Elrejti a bal oldali élt (alapértelmezett érték false) – meghatározza a keret doboz bal élének rejtett vagy látható állapotát. |
| [getHideRight()](#getHideRight--) | Elrejti a jobb oldali élt (alapértelmezett érték false) – meghatározza a keret doboz jobb élének rejtett vagy látható állapotát. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Elrejti a jobb oldali élt (alapértelmezett érték false) – meghatározza a keret doboz jobb élének rejtett vagy látható állapotát. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Áthúzott vízszintes vonal (alapértelmezett érték false) – meghatározza a vízszintes áthúzott vonal rejtett vagy látható állapotát. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Áthúzott vízszintes vonal (alapértelmezett érték false) – meghatározza a vízszintes áthúzott vonal rejtett vagy látható állapotát. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Áthúzott függőleges vonal (alapértelmezett érték false) – meghatározza a függőleges áthúzott vonal rejtett vagy látható állapotát. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Áthúzott függőleges vonal (alapértelmezett érték false) – meghatározza a függőleges áthúzott vonal rejtett vagy látható állapotát. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Áthúzott bal alsó-től jobb felsőig (alapértelmezett érték false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Áthúzott bal alsó-től jobb felsőig (alapértelmezett érték false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Áthúzott bal felső-től jobb alsóig (alapértelmezett érték false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Áthúzott bal felső-től jobb alsóig (alapértelmezett érték false). |
| [getChildren()](#getChildren--) | Gyermekelemek lekérése |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Kontrol karakter tulajdonságok |

### MathBorderBox(IMathElement element) {#MathBorderBox-com.aspose.slides.IMathElement-}
```
public MathBorderBox(IMathElement element)
```

Létrehozza a MathBorderBox elemet téglalap alakú kerettel

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Az az alap elem, amelyhez a keret doboz alkalmazva van. Lehet null. |

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
| element | [IMathElement](../../com.aspose.slides/imathelement) | Az az alap elem, amelyhez a keret doboz alkalmazva van |
| hideTop | boolean | Felső él elrejtése |
| hideBottom | boolean | Alsó él elrejtése |
| hideLeft | boolean | Bal oldali él elrejtése |
| hideRight | boolean | Jobb oldali él elrejtése |
| strikethroughHorizontal | boolean | Áthúzott vízszintes vonal |
| strikethroughVertical | boolean | Áthúzott függőleges vonal |
| strikethroughBottomLeftToTopRight | boolean | Áthúzott bal alsó-től jobb felsőig |
| strikethroughTopLeftToBottomRight | boolean | Áthúzott bal felső-től jobb alsóig |

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

**Visszatér:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public final boolean getHideTop()
```

Elrejti a felső élt (alapértelmezett érték false) – meghatározza a keret doboz felső élének rejtett vagy látható állapotát.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**Visszatér:**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public final void setHideTop(boolean value)
```

Elrejti a felső élt (alapértelmezett érték false) – meghatározza a keret doboz felső élének rejtett vagy látható állapotát.

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

Elrejti az alsó élt (alapértelmezett érték false) – meghatározza a keret doboz alsó élének rejtett vagy látható állapotát.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**Visszatér:**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public final void setHideBottom(boolean value)
```

Elrejti az alsó élt (alapértelmezett érték false) – meghatározza a keret doboz alsó élének rejtett vagy látható állapotát.

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

Elrejti a bal oldali élt (alapértelmezett érték false) – meghatározza a keret doboz bal élének rejtett vagy látható állapotát.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**Visszatér:**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public final void setHideLeft(boolean value)
```

Elrejti a bal oldali élt (alapértelmezett érték false) – meghatározza a keret doboz bal élének rejtett vagy látható állapotát.

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

Elrejti a jobb oldali élt (alapértelmezett érték false) – meghatározza a keret doboz jobb élének rejtett vagy látható állapotát.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**Visszatér:**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public final void setHideRight(boolean value)
```

Elrejti a jobb oldali élt (alapértelmezett érték false) – meghatározza a keret doboz jobb élének rejtett vagy látható állapotát.

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

Áthúzott vízszintes vonal (alapértelmezett érték false) – meghatározza a vízszintes áthúzott vonal rejtett vagy látható állapotát.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Visszatér:**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public final void setStrikethroughHorizontal(boolean value)
```

Áthúzott vízszintes vonal (alapértelmezett érték false) – meghatározza a vízszintes áthúzott vonal rejtett vagy látható állapotát.

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

Áthúzott függőleges vonal (alapértelmezett érték false) – meghatározza a függőleges áthúzott vonal rejtett vagy látható állapotát.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**Visszatér:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public final void setStrikethroughVertical(boolean value)
```

Áthúzott függőleges vonal (alapértelmezett érték false) – meghatározza a függőleges áthúzott vonal rejtett vagy látható állapotát.

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

Áthúzott bal alsó-től jobb felsőig (alapértelmezett érték false). Meghatározza a bal alsó sarokból a jobb felső sarokba ívelő áthúzott átló rejtett vagy látható állapotát.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Visszatér:**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public final void setStrikethroughBottomLeftToTopRight(boolean value)
```

Áthúzott bal alsó-től jobb felsőig (alapértelmezett érték false). Meghatározza a bal alsó sarokból a jobb felső sarokba ívelő áthúzott átló rejtett vagy látható állapotát.

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

Áthúzott bal felső-től jobb alsóig (alapértelmezett érték false). Meghatározza a bal felső sarokból a jobb alsó sarokba ívelő áthúzott átló rejtett vagy látható állapotát.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Visszatér:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public final void setStrikethroughTopLeftToBottomRight(boolean value)
```

Áthúzott bal felső-től jobb alsóig (alapértelmezett érték false). Meghatározza a bal felső sarokból a jobb alsó sarokba ívelő áthúzott átló rejtett vagy látható állapotát.

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

**Visszatér:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Kontrol karakter tulajdonságok

**Visszatér:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps