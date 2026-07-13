---
title: MathBar
second_title: Aspose.Slides dla Androida poprzez dokumentację API Java
description: Określa funkcję kreski, składającą się z argumentu bazowego oraz kreski nad lub pod
type: docs
url: /pl/com.aspose.slides/mathbar/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathBar](../../com.aspose.slides/imathbar), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBar extends MathElementBase implements IMathBar, IHasControlCharacterProperties
```

Określa funkcję kreski, składającą się z argumentu bazowego oraz kreski nad lub pod

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [MathBar(IMathElement element)](#MathBar-com.aspose.slides.IMathElement-) | Inicjalizuje MathBar z kreską nad (pozycja Top) |
| [MathBar(IMathElement element, int position)](#MathBar-com.aspose.slides.IMathElement-int-) | Inicjalizuje MathBar z określoną pozycją |
## Metody

| Metoda | Opis |
| --- | --- |
| [getBase()](#getBase--) | Argument bazowy |
| [getPosition()](#getPosition--) | Pozycja linii kreski. |
| [setPosition(int value)](#setPosition-int-) | Pozycja linii kreski. |
| [getChildren()](#getChildren--) | Pobiera elementy potomne |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Właściwości znaków kontrolnych |
### MathBar(IMathElement element) {#MathBar-com.aspose.slides.IMathElement-}
```
public MathBar(IMathElement element)
```


Inicjalizuje MathBar z kreską nad (pozycja Top)

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Element bazowy, do którego stosowana jest kreska |

### MathBar(IMathElement element, int position) {#MathBar-com.aspose.slides.IMathElement-int-}
```
public MathBar(IMathElement element, int position)
```


Inicjalizuje MathBar z określoną pozycją

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"), MathTopBotPositions.Bottom);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Element bazowy, do którego stosowana jest kreska |
| position | int | Pozycja linii kreski. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Argument bazowy

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**Zwraca:**
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public final int getPosition()
```


Pozycja linii kreski. Domyślnie: Top

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Zwraca:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


Pozycja linii kreski. Domyślnie: Top

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Pobiera elementy potomne

**Zwraca:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Właściwości znaków kontrolnych

**Zwraca:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps