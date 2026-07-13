---
title: MathBorderBox
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
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
| [MathBorderBox(IMathElement element)](#MathBorderBox-com.aspose.slides.IMathElement-) | Vytvoří MathBorderBox element s obdélníkovým rámečkem |
| [MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Vytvoří MathBorderBox element |
## Metody

| Metoda | Popis |
| --- | --- |
| [getBase()](#getBase--) | Základní argument |
| [getHideTop()](#getHideTop--) | Skrytí horního okraje (výchozí hodnota je false) - určuje, zda je horní okraj rámečku skrytý nebo zobrazený. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Skrytí horního okraje (výchozí hodnota je false) - určuje, zda je horní okraj rámečku skrytý nebo zobrazený. |
| [getHideBottom()](#getHideBottom--) | Skrytí spodního okraje (výchozí hodnota je false) - určuje, zda je spodní okraj rámečku skrytý nebo zobrazený. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Skrytí spodního okraje (výchozí hodnota je false) - určuje, zda je spodní okraj rámečku skrytý nebo zobrazený. |
| [getHideLeft()](#getHideLeft--) | Skrytí levého okraje (výchozí hodnota je false) - určuje, zda je levý okraj rámečku skrytý nebo zobrazený. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Skrytí levého okraje (výchozí hodnota je false) - určuje, zda je levý okraj rámečku skrytý nebo zobrazený. |
| [getHideRight()](#getHideRight--) | Skrytí pravého okraje (výchozí hodnota je false) - určuje, zda je pravý okraj rámečku skrytý nebo zobrazený. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Skrytí pravého okraje (výchozí hodnota je false) - určuje, zda je pravý okraj rámečku skrytý nebo zobrazený. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Přeškrtnutí vodorovně (výchozí hodnota je false) - určuje, zda je vodorovná přeškrtnutá čára skrytá nebo zobrazena. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Přeškrtnutí vodorovně (výchozí hodnota je false) - určuje, zda je vodorovná přeškrtnutá čára skrytá nebo zobrazena. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Přeškrtnutí svisle (výchozí hodnota je false) - určuje, zda je svislá přeškrtnutá čára skrytá nebo zobrazena. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Přeškrtnutí svisle (výchozí hodnota je false) - určuje, zda je svislá přeškrtnutá čára skrytá nebo zobrazena. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Přeškrtnutí z levého dolního rohu do pravého horního (výchozí hodnota je false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Přeškrtnutí z levého dolního rohu do pravého horního (výchozí hodnota je false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Přeškrtnutí z levého horního rohu do pravého dolního (výchozí hodnota je false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Přeškrtnutí z levého horního rohu do pravého dolního (výchozí hodnota je false). |
| [getChildren()](#getChildren--) | Získá podřízené elementy |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Vlastnosti řídicích znaků |
### MathBorderBox(IMathElement element) {#MathBorderBox-com.aspose.slides.IMathElement-}
```
public MathBorderBox(IMathElement element)
```

Vytvoří MathBorderBox element s obdélníkovým rámečkem

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Základní element, na který se aplikuje rámeček. Může být null. |

### MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Vytvoří MathBorderBox element

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"), true, true, true, false, true, true, true, true)
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Základní element, na který se aplikuje rámeček |
| hideTop | boolean | Skrytí horního okraje |
| hideBottom | boolean | Skrytí spodního okraje |
| hideLeft | boolean | Skrytí levého okraje |
| hideRight | boolean | Skrytí pravého okraje |
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

Skrytí horního okraje (výchozí hodnota je false) - určuje, zda je horní okraj rámečku skrytý nebo zobrazený.

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

Skrytí horního okraje (výchozí hodnota je false) - určuje, zda je horní okraj rámečku skrytý nebo zobrazený.

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

Skrytí spodního okraje (výchozí hodnota je false) - určuje, zda je spodní okraj rámečku skrytý nebo zobrazený.

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

Skrytí spodního okraje (výchozí hodnota je false) - určuje, zda je spodní okraj rámečku skrytý nebo zobrazený.

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

Skrytí levého okraje (výchozí hodnota je false) - určuje, zda je levý okraj rámečku skrytý nebo zobrazený.

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

Skrytí levého okraje (výchozí hodnota je false) - určuje, zda je levý okraj rámečku skrytý nebo zobrazený.

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

Skrytí pravého okraje (výchozí hodnota je false) - určuje, zda je pravý okraj rámečku skrytý nebo zobrazený.

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

Skrytí pravého okraje (výchozí hodnota je false) - určuje, zda je pravý okraj rámečku skrytý nebo zobrazený.

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

Přeškrtnutí vodorovně (výchozí hodnota je false) - určuje, zda je vodorovná přeškrtnutá čára skrytá nebo zobrazena.

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

Přeškrtnutí vodorovně (výchozí hodnota je false) - určuje, zda je vodorovná přeškrtnutá čára skrytá nebo zobrazena.

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

Přeškrtnutí svisle (výchozí hodnota je false) - určuje, zda je svislá přeškrtnutá čára skrytá nebo zobrazena.

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

Přeškrtnutí svisle (výchozí hodnota je false) - určuje, zda je svislá přeškrtnutá čára skrytá nebo zobrazena.

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

Přeškrtnutí z levého dolního rohu do pravého horního (výchozí hodnota je false). Určuje, zda je úhlopříčná přeškrtnutá čára z levého dolního rohu do pravého horního rohu rámečku skrytá nebo zobrazena.

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

Přeškrtnutí z levého dolního rohu do pravého horního (výchozí hodnota je false). Určuje, zda je úhlopříčná přeškrtnutá čára z levého dolního rohu do pravého horního rohu rámečku skrytá nebo zobrazena.

--------------------

> ```
> Example:
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

Přeškrtnutí z levého horního rohu do pravého dolního (výchozí hodnota je false). Určuje, zda je úhlopříčná přeškrtnutá čára z levého horního rohu do pravého dolního rohu rámečku skrytá nebo zobrazena.

--------------------

> ```
> Example:
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

Přeškrtnutí z levého horního rohu do pravého dolního (výchozí hodnota je false). Určuje, zda je úhlopříčná přeškrtnutá čára z levého horního rohu do pravého dolního rohu rámečku skrytá nebo zobrazena.

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

Získá podřízené elementy

**Vrací:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Vlastnosti řídicích znaků

**Vrací:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps