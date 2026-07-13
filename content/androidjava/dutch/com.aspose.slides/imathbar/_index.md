---
title: IMathBar
second_title: Aspose.Slides voor Android via Java API-referentie
description: Specificeert de bar-functie bestaande uit een basisargument en een boven- of onderstreepte balk
type: docs
url: /nl/com.aspose.slides/imathbar/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBar extends IMathElement
```

Specificeert de bar-functie, bestaande uit een basisargument en een boven- of onderstreepte balk

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getBase()](#getBase--) | Basisargument |
| [getPosition()](#getPosition--) | Positie van de balklijn. |
| [setPosition(int value)](#setPosition-int-) | Positie van de balklijn. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Basisargument

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**Retourwaarde:**
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


Positie van de balklijn. Standaard: Boven

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Retourwaarde:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


Positie van de balklijn. Standaard: Boven

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |