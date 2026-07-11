---
title: IMathBar
second_title: Aspose.Slides для Android через справочник API Java
description: Указывает функцию черты, состоящую из базового аргумента и надчерты или подчерты
type: docs
url: /ru/com.aspose.slides/imathbar/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBar extends IMathElement
```

Указывает функцию черты, состоящую из базового аргумента и надчерты или подчерты

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## Методы

| Метод | Описание |
| --- | --- |
| [getBase()](#getBase--) | Базовый аргумент |
| [getPosition()](#getPosition--) | Позиция линии черты. |
| [setPosition(int value)](#setPosition-int-) | Позиция линии черты. |
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


Позиция линии черты. По умолчанию: Top

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


Позиция линии черты. По умолчанию: Top

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |