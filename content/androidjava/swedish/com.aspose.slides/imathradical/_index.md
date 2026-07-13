---
title: IMathRadical
second_title: Aspose.Slides för Android via Java API-referens
description: Specificerar radikalfunktionen som består av en bas och en valfri grad.
type: docs
url: /sv/com.aspose.slides/imathradical/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRadical extends IMathElement
```

Specificerar radikalfunktionen, bestående av en bas och en valfri grad. Exempel på radikalobjekt är \\u221a\\ud835\\udc65.

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // kubrot
```
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBase()](#getBase--) | Basargument |
| [getDegree()](#getDegree--) | Gradargument |
| [getHideDegree()](#getHideDegree--) | Dölj grad När är sant visas inte graden, som i \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | Dölj grad När är sant visas inte graden, som i \\u221a\\ud835\\udc65 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Basargument

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // kubrot
>  IMathElement baseElem = radical.getBase();
```

**Returnerar:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public abstract IMathElement getDegree()
```

Gradargument

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // kubrot
>  IMathElement degreeElem = radical.getDegree();
> ```

**Returnerar:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public abstract boolean getHideDegree()
```

Dölj grad När är sant visas inte graden, som i \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // kubrot
>  radical.setHideDegree(true);
> ```

**Returnerar:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public abstract void setHideDegree(boolean value)
```

Dölj grad När är sant visas inte graden, som i \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // kubrot
>  radical.setHideDegree(true);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |