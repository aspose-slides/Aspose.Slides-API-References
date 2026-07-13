---
title: IMathBar
second_title: Aspose.Slides för Android via Java API-referens
description: Specificerar bar-funktionen, bestående av ett basargument och ett överstreck eller understreck
type: docs
url: /sv/com.aspose.slides/imathbar/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBar extends IMathElement
```

Specificerar bar-funktionen, bestående av ett basargument och ett överstreck eller understreck

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBase()](#getBase--) | Basargument |
| [getPosition()](#getPosition--) | Position för strecket. |
| [setPosition(int value)](#setPosition-int-) | Position för strecket. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Basargument

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**Returnerar:**
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


Position för strecket. Standard: Överst

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Returnerar:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


Position för strecket. Standard: Överst

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |