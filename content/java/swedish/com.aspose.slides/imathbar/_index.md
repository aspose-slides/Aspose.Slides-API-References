---
title: IMathBar
second_title: Aspose.Slides för Java API-referens
description: Specificerar stapelfunktionen som består av ett basargument och en över- eller underlinje
type: docs
url: /sv/com.aspose.slides/imathbar/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBar extends IMathElement
```

Specificerar stapelfunktionen, bestående av ett basargument och en över- eller underlinje

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
| [getPosition()](#getPosition--) | Position för stapellinjen. |
| [setPosition(int value)](#setPosition-int-) | Position för stapellinjen. |
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


Position för stapellinjen. Standard: Överst

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


Position för stapellinjen. Standard: Överst

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