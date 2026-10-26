---
title: IMathBar
second_title: Aspose.Slides for Java API Referenciája
description: Meghatározza a sáv függvényt, amely egy alap argumentumot és egy felül- vagy alulvonatot tartalmaz
type: docs
url: /hu/com.aspose.slides/imathbar/
---
**Az összes megvalósított interfész:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBar extends IMathElement
```

Meghatározza a sáv függvényt, amely egy alap argumentumból és egy felül- vagy alulvonalból áll

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## Módszerek

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Alap argumentum |
| [getPosition()](#getPosition--) | A vonal helyzete. |
| [setPosition(int value)](#setPosition-int-) | A vonal helyzete. |
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
> ```

**Visszaadja:**
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


A vonal helyzete. Alapértelmezett: Fent

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Visszaadja:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


A vonal helyzete. Alapértelmezett: Fent

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