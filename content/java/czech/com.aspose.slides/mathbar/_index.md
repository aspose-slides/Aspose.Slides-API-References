---
title: MathBar
second_title: Aspose.Slides pro Java – referenční příručka API
description: Specifikuje funkci pruhu, která se skládá ze základního argumentu a horní nebo spodní čáry
type: docs
url: /cs/com.aspose.slides/mathbar/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**All Implemented Interfaces:**  
[com.aspose.slides.IMathBar](../../com.aspose.slides/imathbar), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathBar extends MathElementBase implements IMathBar, IHasControlCharacterProperties
```

Specifies the bar function, consisting of a base argument and an overbar or underbar

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## Konstruktory

| Constructor | Description |
| --- | --- |
| [MathBar(IMathElement element)](#MathBar-com.aspose.slides.IMathElement-) | Inicializuje MathBar s horní čárou (Top position) |
| [MathBar(IMathElement element, int position)](#MathBar-com.aspose.slides.IMathElement-int-) | Inicializuje MathBar se zadanou pozicí |
## Metody

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Základní argument |
| [getPosition()](#getPosition--) | Pozice čáry. |
| [setPosition(int value)](#setPosition-int-) | Pozice čáry. |
| [getChildren()](#getChildren--) | Získá podřazené prvky |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Vlastnosti řídicích znaků |
### MathBar(IMathElement element) {#MathBar-com.aspose.slides.IMathElement-}
```
public MathBar(IMathElement element)
```


Inicializuje MathBar s horní čárou (Top position)

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Základní prvek, na který se čára aplikuje |

### MathBar(IMathElement element, int position) {#MathBar-com.aspose.slides.IMathElement-int-}
```
public MathBar(IMathElement element, int position)
```


Inicializuje MathBar se zadanou pozicí

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"), MathTopBotPositions.Bottom);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Základní prvek, na který se čára aplikuje |
| position | int | Pozice čáry. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Základní argument

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**Návratová hodnota:**
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public final int getPosition()
```


Pozice čáry. Default: Top

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Návratová hodnota:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


Pozice čáry. Default: Top

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Získá podřazené prvky

**Návratová hodnota:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Vlastnosti řídicích znaků

**Návratová hodnota:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps