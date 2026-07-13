---
title: MathBar
second_title: Aspose.Slides voor Android via Java API-referentie
description: Specificeert de balkfunctie die bestaat uit een basisargument en een overbalk of onderbalk
type: docs
url: /nl/com.aspose.slides/mathbar/
---
**Overerving:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathBar](../../com.aspose.slides/imathbar), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBar extends MathElementBase implements IMathBar, IHasControlCharacterProperties
```

Specificeert de balkfunctie, bestaande uit een basisargument en een overbalk of onderbalk

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [MathBar(IMathElement element)](#MathBar-com.aspose.slides.IMathElement-) | Initialiseert MathBar met overbalk (Bovenpositie) |
| [MathBar(IMathElement element, int position)](#MathBar-com.aspose.slides.IMathElement-int-) | Initialiseert MathBar met gespecificeerde positie |
## Methods

| Methode | Beschrijving |
| --- | --- |
| [getBase()](#getBase--) | Basisargument |
| [getPosition()](#getPosition--) | Positie van de balklijn. |
| [setPosition(int value)](#setPosition-int-) | Positie van de balklijn. |
| [getChildren()](#getChildren--) | Haalt onderliggende elementen op |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Controlekaraktereigenschappen |
### MathBar(IMathElement element) {#MathBar-com.aspose.slides.IMathElement-}
```
public MathBar(IMathElement element)
```


Initialiseert MathBar met overbalk (Bovenpositie)

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Het basis-element waarop de balk wordt toegepast |

### MathBar(IMathElement element, int position) {#MathBar-com.aspose.slides.IMathElement-int-}
```
public MathBar(IMathElement element, int position)
```


Initialiseert MathBar met gespecificeerde positie

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"), MathTopBotPositions.Bottom);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Het basis-element waarop de balk wordt toegepast |
| position | int | Positie van de balklijn. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Basisargument

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**Retour:**
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public final int getPosition()
```


Positie van de balklijn. Standaard: Boven

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Retour:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


Positie van de balklijn. Standaard: Boven

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Haalt onderliggende elementen op

**Retour:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Controlekaraktereigenschappen

**Retour:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps