---
title: IMathRadical
second_title: Aspose.Slides Androidra a Java API hivatkozásán keresztül
description: Meghatározza a gyökfüggvényt, amely egy alapból és egy opcionális fokból áll.
type: docs
url: /hu/com.aspose.slides/imathradical/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRadical extends IMathElement
```

Meghatározza a gyökfüggvényt, amely egy alapból és egy opcionális fokból áll. A gyökobjektus példája: \\u221a\\ud835\\udc65.

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // kockagyök
> ```
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getBase()](#getBase--) | Alap argumentum |
| [getDegree()](#getDegree--) | Fok argumentum |
| [getHideDegree()](#getHideDegree--) | Elrejtett fok: Ha true, a fok nem jelenik meg, ahogyan a \\u221a\\ud835\\udc65-nál |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | Elrejtett fok: Ha true, a fok nem jelenik meg, ahogyan a \\u221a\\ud835\\udc65-nál |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Alap argumentum

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // kockagyök
>  IMathElement baseElem = radical.getBase();
>  ```

**Visszatér:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public abstract IMathElement getDegree()
```


Fok argumentum

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // kockagyök
>  IMathElement degreeElem = radical.getDegree();
>  ```

**Visszatér:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public abstract boolean getHideDegree()
```


Elrejtett fok: Ha true, a fok nem jelenik meg, ahogyan a \\u221a\\ud835\\udc65-nál

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // kockagyök
>  radical.setHideDegree(true);
> ```

**Visszatér:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public abstract void setHideDegree(boolean value)
```


Elrejtett fok: Ha true, a fok nem jelenik meg, ahogyan a \\u221a\\ud835\\udc65-nál

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // kockagyök
>  radical.setHideDegree(true);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |