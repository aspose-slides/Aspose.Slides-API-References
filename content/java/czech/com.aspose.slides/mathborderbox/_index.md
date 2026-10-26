---
title: MathBorderBox
second_title: Aspose.Slides pro Java API Reference
description: Vykresluje obdélníkový nebo jiný rámeček kolem IMathElement.
type: docs
url: /cs/com.aspose.slides/mathborderbox/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Všechny implementované rozhraní:**
[com.aspose.slides.IMathBorderBox](../../com.aspose.slides/imathborderbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBorderBox extends MathElementBase implements IMathBorderBox, IHasControlCharacterProperties
```

Vykresluje obdélníkový nebo jiný rámeček kolem IMathElement.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [MathBorderBox(IMathElement element)](#MathBorderBox-com.aspose.slides.IMathElement-) | Vytvoří prvek MathBorderBox s obdélníkovým rámečkem |
| [MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Vytvoří prvek MathBorderBox |
## Metody

| Metoda | Popis |
| --- | --- |
| [getBase()](#getBase--) | Základní argument |
| [getHideTop()](#getHideTop--) | Skrýt horní okraj (výchozí hodnota je false) – určuje skrytý nebo zobrazený stav horního okraje rámečku. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Skrýt horní okraj (výchozí hodnota je false) – určuje skrytý nebo zobrazený stav horního okraje rámečku. |
| [getHideBottom()](#getHideBottom--) | Skrýt spodní okraj (výchozí hodnota je false) – určuje skrytý nebo zobrazený stav spodního okraje rámečku. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Skrýt spodní okraj (výchozí hodnota je false) – určuje skrytý nebo zobrazený stav spodního okraje rámečku. |
| [getHideLeft()](#getHideLeft--) | Skrýt levý okraj (výchozí hodnota je false) – určuje skrytý nebo zobrazený stav levého okraje rámečku. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Skrýt levý okraj (výchozí hodnota je false) – určuje skrytý nebo zobrazený stav levého okraje rámečku. |
| [getHideRight()](#getHideRight--) | Skrýt pravý okraj (výchozí hodnota je false) – určuje skrytý nebo zobrazený stav pravého okraje rámečku. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Skrýt pravý okraj (výchozí hodnota je false) – určuje skrytý nebo zobrazený stav pravého okraje rámečku. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Přeškrtnutí vodorovně (výchozí hodnota je false) – určuje skrytý nebo zobrazený stav vodorovné přeškrtnuté čáry. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Přeškrtnutí vodorovně (výchozí hodnota je false) – určuje skrytý nebo zobrazený stav vodorovné přeškrtnuté čáry. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Přeškrtnutí svisle (výchozí hodnota je false) – určuje skrytý nebo zobrazený stav svislé přeškrtnuté čáry. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Přeškrtnutí svisle (výchozí hodnota je false) – určuje skrytý nebo zobrazený stav svislé přeškrtnuté čáry. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Přeškrtnutí z levého dolního rohu do pravého horního (výchozí hodnota je false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Přeškrtnutí z levého dolního rohu do pravého horního (výchozí hodnota je false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Přeškrtnutí z levého horního rohu do pravého dolního (výchozí hodnota je false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Přeškrtnutí z levého horního rohu do pravého dolního (výchozí hodnota je false). |
| [getChildren()](#getChildren--) | Získat podřízené prvky |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Vlastnosti řídicích znaků |
### MathBorderBox(IMathElement element) {#MathBorderBox-com.aspose.slides.IMathElement-}
```
public MathBorderBox(IMathElement element)
```


Vytvoří prvek MathBorderBox s obdélníkovým rámečkem

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Základní prvek, na který se aplikuje rámeček. Může být null. |

### MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


Vytvoří prvek MathBorderBox

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"), true, true, true, false, true, true, true, true)
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Základní prvek, na který se aplikuje rámeček |
| hideTop | boolean | Skrýt horní okraj |
| hideBottom | boolean | Skrýt spodní okraj |
| hideLeft | boolean | Skrýt levý okraj |
| hideRight | boolean | Skrýt pravý okraj |
| strikethroughHorizontal | boolean | Přeškrtnutí vodorovně |
| strikethroughVertical | boolean | Přeškrtnutí svisle |
| strikethroughBottomLeftToTopRight | boolean | Přeškrtnutí z levého dolního rohu do pravého horního |
| strikethroughTopLeftToBottomRight | boolean | Přeškrtnutí z levého horního rohu do pravého dolního |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Základní argument

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  IMathElement base = borderBox.getBase();
> ```

**Vrací:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public final boolean getHideTop()
```


Skrýt horní okraj (výchozí hodnota je false) – určuje skrytý nebo zobrazený stav horního okraje rámečku.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**Vrací:**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public final void setHideTop(boolean value)
```


Skrýt horní okraj (výchozí hodnota je false) – určuje skrytý nebo zobrazený stav horního okraje rámečku.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public final boolean getHideBottom()
```


Skrýt spodní okraj (výchozí hodnota je false) – určuje skrytý nebo zobrazený stav spodního okraje rámečku.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**Vrací:**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public final void setHideBottom(boolean value)
```


Skrýt spodní okraj (výchozí hodnota je false) – určuje skrytý nebo zobrazený stav spodního okraje rámečku.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public final boolean getHideLeft()
```


Skrýt levý okraj (výchozí hodnota je false) – určuje skrytý nebo zobrazený stav levého okraje rámečku.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**Vrací:**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public final void setHideLeft(boolean value)
```


Skrýt levý okraj (výchozí hodnota je false) – určuje skrytý nebo zobrazený stav levého okraje rámečku.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public final boolean getHideRight()
```


Skrýt pravý okraj (výchozí hodnota je false) – určuje skrytý nebo zobrazený stav pravého okraje rámečku.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**Vrací:**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public final void setHideRight(boolean value)
```


Skrýt pravý okraj (výchozí hodnota je false) – určuje skrytý nebo zobrazený stav pravého okraje rámečku.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public final boolean getStrikethroughHorizontal()
```


Přeškrtnutí vodorovně (výchozí hodnota je false) – určuje skrytý nebo zobrazený stav vodorovné přeškrtnuté čáry.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Vrací:**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public final void setStrikethroughHorizontal(boolean value)
```


Přeškrtnutí vodorovně (výchozí hodnota je false) – určuje skrytý nebo zobrazený stav vodorovné přeškrtnuté čáry.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public final boolean getStrikethroughVertical()
```


Přeškrtnutí svisle (výchozí hodnota je false) – určuje skrytý nebo zobrazený stav svislé přeškrtnuté čáry.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**Vrací:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public final void setStrikethroughVertical(boolean value)
```


Přeškrtnutí svisle (výchozí hodnota je false) – určuje skrytý nebo zobrazený stav svislé přeškrtnuté čáry.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public final boolean getStrikethroughBottomLeftToTopRight()
```


Přeškrtnutí z levého dolního rohu do pravého horního (výchozí hodnota je false). Určuje skrytý nebo zobrazený stav přeškrtnuté diagonální čáry od levého dolního rohu k pravému hornímu rohu rámečku.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Vrací:**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public final void setStrikethroughBottomLeftToTopRight(boolean value)
```


Přeškrtnutí z levého dolního rohu do pravého horního (výchozí hodnota je false). Určuje skrytý nebo zobrazený stav přeškrtnuté diagonální čáry od levého dolního rohu k pravému hornímu rohu rámečku.

--------------------

> ```
> Příklad:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public final boolean getStrikethroughTopLeftToBottomRight()
```


Přeškrtnutí z levého horního rohu do pravého dolního (výchozí hodnota je false). Určuje skrytý nebo zobrazený stav přeškrtnuté diagonální čáry od levého horního rohu k pravému dolnímu rohu rámečku.

--------------------

> ```
> Příklad:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Vrací:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public final void setStrikethroughTopLeftToBottomRight(boolean value)
```


Přeškrtnutí z levého horního rohu do pravého dolního (výchozí hodnota je false). Určuje skrytý nebo zobrazený stav přeškrtnuté diagonální čáry od levého horního rohu k pravému dolnímu rohu rámečku.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Získat podřízené prvky

**Vrací:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Vlastnosti řídicích znaků

**Vrací:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps