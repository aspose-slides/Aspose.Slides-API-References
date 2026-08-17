---
title: IMathBar
second_title: Aspose.Slides для Java API справочник
description: Определяет функцию штриха, состоящую из базового аргумента и надстрочного или подстрочного
type: docs
url: /ru/com.aspose.slides/imathbar/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBar extends IMathElement
```

Определяет функцию штриха, состоящую из базового аргумента и надстрочного или подстрочного

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## Методы

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Базовый аргумент |
| [getPosition()](#getPosition--) | Позиция линии штриха. |
| [setPosition(int value)](#setPosition-int-) | Позиция линии штриха. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Базовый аргумент

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**Возвращаемое значение:**
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


Позиция линии штриха. По умолчанию: Top

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Возвращаемое значение:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


Позиция линии штриха. По умолчанию: Top

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |