---
title: IMathLimit
second_title: Справочник API Aspose.Slides для Java
description: Указывает объект Limit, состоящий из текста на базовой линии и уменьшенного текста непосредственно над ним или под ним.
type: docs
url: /ru/com.aspose.slides/imathlimit/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathLimit extends IMathElement
```

Указывает объект Limit, состоящий из текста на базовой линии и уменьшенного текста сразу над ней или под ней.

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
> ```
## Методы

| Метод | Описание |
| --- | --- |
| [getBase()](#getBase--) | Аргумент Base |
| [getLimit()](#getLimit--) | Аргумент Limit |
| [getUpperLimit()](#getUpperLimit--) | Указывает верхнюю или нижнюю границу |
| [setUpperLimit(boolean value)](#setUpperLimit-boolean-) | Указывает верхнюю или нижнюю границу |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Аргумент Base

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  IMathElement baseArg = limitElement.getBase();
> ```

**Возвращаемое значение:**
[IMathElement](../../com.aspose.slides/imathelement)
### getLimit() {#getLimit--}
```
public abstract IMathElement getLimit()
```


Аргумент Limit

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  IMathElement limitArg = limitElement.getLimit();
> ```

**Возвращаемое значение:**
[IMathElement](../../com.aspose.slides/imathelement)
### getUpperLimit() {#getUpperLimit--}
```
public abstract boolean getUpperLimit()
```


Указывает верхнюю или нижнюю границу

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  limitElement.setUpperLimit(false);
> ```

**Возвращаемое значение:**
boolean
### setUpperLimit(boolean value) {#setUpperLimit-boolean-}
```
public abstract void setUpperLimit(boolean value)
```


Указывает верхнюю или нижнюю границу

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  limitElement.setUpperLimit(false);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |