---
title: IMathBar
second_title: Aspose.Slides Android számára a Java API hivatkozás alapján
description: Meghatározza a bar függvényt, amely egy alap argumentumból és egy felül vagy alávonásból áll
type: docs
url: /hu/com.aspose.slides/imathbar/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBar extends IMathElement
```

Meghatározza a bar függvényt, amely egy alap argumentumból és egy felül- vagy alávonásból áll

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getBase()](#getBase--) | Alap argumentum |
| [getPosition()](#getPosition--) | A vonal pozíciója. |
| [setPosition(int value)](#setPosition-int-) | A vonal pozíciója. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Alap argumentum

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
>  ```

**Visszatér:**
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


A vonal pozíciója. Alapértelmezett: Top

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Visszatér:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


A vonal pozíciója. Alapértelmezett: Top

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |