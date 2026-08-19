---
title: IMathBorderBox
second_title: Aspose.Slides pro Java API Reference
description: Vykresluje obdélníkový nebo jiný rámeček kolem IMathElement.
type: docs
url: /cs/com.aspose.slides/imathborderbox/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBorderBox extends IMathElement
```

Kreslí obdélníkový nebo jiný rámeček kolem IMathElement.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```
## Metody

| Metoda | Popis |
| --- | --- |
| [getBase()](#getBase--) | Základní argument |
| [getHideTop()](#getHideTop--) | Skrytí horní hrany (výchozí hodnota je false) – určuje skrytý nebo zobrazovaný stav horní hrany ohraničovacího rámečku. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Skrytí horní hrany (výchozí hodnota je false) – určuje skrytý nebo zobrazovaný stav horní hrany ohraničovacího rámečku. |
| [getHideBottom()](#getHideBottom--) | Skrytí spodní hrany (výchozí hodnota je false) – určuje skrytý nebo zobrazovaný stav spodní hrany ohraničovacího rámečku. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Skrytí spodní hrany (výchozí hodnota je false) – určuje skrytý nebo zobrazovaný stav spodní hrany ohraničovacího rámečku. |
| [getHideLeft()](#getHideLeft--) | Skrytí levé hrany (výchozí hodnota je false) – určuje skrytý nebo zobrazovaný stav levé hrany ohraničovacího rámečku. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Skrytí levé hrany (výchozí hodnota je false) – určuje skrytý nebo zobrazovaný stav levé hrany ohraničovacího rámečku. |
| [getHideRight()](#getHideRight--) | Skrytí pravé hrany (výchozí hodnota je false) – určuje skrytý nebo zobrazovaný stav pravé hrany ohraničovacího rámečku. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Skrytí pravé hrany (výchozí hodnota je false) – určuje skrytý nebo zobrazovaný stav pravé hrany ohraničovacího rámečku. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Přeškrtnutí vodorovné (výchozí hodnota je false) – určuje skrytý nebo zobrazovaný stav vodorovné přeškrtnuté čáry. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Přeškrtnutí vodorovné (výchozí hodnota je false) – určuje skrytý nebo zobrazovaný stav vodorovné přeškrtnuté čáry. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Přeškrtnutí svislé (výchozí hodnota je false) – určuje skrytý nebo zobrazovaný stav svislé přeškrtnuté čáry. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Přeškrtnutí svislé (výchozí hodnota je false) – určuje skrytý nebo zobrazovaný stav svislé přeškrtnuté čáry. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Přeškrtnutí z levého dolního rohu do pravého horního (výchozí hodnota je false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Přeškrtnutí z levého dolního rohu do pravého horního (výchozí hodnota je false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Přeškrtnutí z levého horního rohu do pravého dolního (výchozí hodnota je false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Přeškrtnutí z levého horního rohu do pravého dolního (výchozí hodnota je false). |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Základní argument

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  IMathElement base = borderBox.getBase();
> ```

**Vrací:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public abstract boolean getHideTop()
```


Skrytí horní hrany (výchozí hodnota je false) – určuje skrytý nebo zobrazovaný stav horní hrany ohraničovacího rámečku.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**Vrací:**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public abstract void setHideTop(boolean value)
```


Skrytí horní hrany (výchozí hodnota je false) – určuje skrytý nebo zobrazovaný stav horní hrany ohraničovacího rámečku.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public abstract boolean getHideBottom()
```


Skrytí spodní hrany (výchozí hodnota je false) – určuje skrytý nebo zobrazovaný stav spodní hrany ohraničovacího rámečku.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**Vrací:**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public abstract void setHideBottom(boolean value)
```


Skrytí spodní hrany (výchozí hodnota je false) – určuje skrytý nebo zobrazovaný stav spodní hrany ohraničovacího rámečku.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public abstract boolean getHideLeft()
```


Skrytí levé hrany (výchozí hodnota je false) – určuje skrytý nebo zobrazovaný stav levé hrany ohraničovacího rámečku.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**Vrací:**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public abstract void setHideLeft(boolean value)
```


Skrytí levé hrany (výchozí hodnota je false) – určuje skrytý nebo zobrazovaný stav levé hrany ohraničovacího rámečku.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public abstract boolean getHideRight()
```


Skrytí pravé hrany (výchozí hodnota je false) – určuje skrytý nebo zobrazovaný stav pravé hrany ohraničovacího rámečku.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**Vrací:**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public abstract void setHideRight(boolean value)
```


Skrytí pravé hrany (výchozí hodnota je false) – určuje skrytý nebo zobrazovaný stav pravé hrany ohraničovacího rámečku.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public abstract boolean getStrikethroughHorizontal()
```


Přeškrtnutí vodorovné (výchozí hodnota je false) – určuje skrytý nebo zobrazovaný stav vodorovné přeškrtnuté čáry.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Vrací:**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public abstract void setStrikethroughHorizontal(boolean value)
```


Přeškrtnutí vodorovné (výchozí hodnota je false) – určuje skrytý nebo zobrazovaný stav vodorovné přeškrtnuté čáry.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public abstract boolean getStrikethroughVertical()
```


Přeškrtnutí svislé (výchozí hodnota je false) – určuje skrytý nebo zobrazovaný stav svislé přeškrtnuté čáry.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**Vrací:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public abstract void setStrikethroughVertical(boolean value)
```


Přeškrtnutí svislé (výchozí hodnota je false) – určuje skrytý nebo zobrazovaný stav svislé přeškrtnuté čáry.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public abstract boolean getStrikethroughBottomLeftToTopRight()
```


Přeškrtnutí z levého dolního rohu do pravého horního (výchozí hodnota je false). Určuje skrytý nebo zobrazovaný stav přeškrtnuté úhloprické čáry od levého dolního rohu k pravému hornímu rohu ohraničovacího rámečku.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Vrací:**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public abstract void setStrikethroughBottomLeftToTopRight(boolean value)
```


Přeškrtnutí z levého dolního rohu do pravého horního (výchozí hodnota je false). Určuje skrytý nebo zobrazovaný stav přeškrtnuté úhloprické čáry od levého dolního rohu k pravému hornímu rohu ohraničovacího rámečku.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public abstract boolean getStrikethroughTopLeftToBottomRight()
```


Přeškrtnutí z levého horního rohu do pravého dolního (výchozí hodnota je false). Určuje skrytý nebo zobrazovaný stav přeškrtnuté úhloprické čáry od levého horního rohu k pravému dolnímu rohu ohraničovacího rámečku.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Vrací:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public abstract void setStrikethroughTopLeftToBottomRight(boolean value)
```


Přeškrtnutí z levého horního rohu do pravého dolního (výchozí hodnota je false). Určuje skrytý nebo zobrazovaný stav přeškrtnuté úhloprické čáry od levého horního rohu k pravému dolnímu rohu ohraničovacího rámečku.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |