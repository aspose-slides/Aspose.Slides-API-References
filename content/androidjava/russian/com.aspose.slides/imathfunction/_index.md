---
title: IMathFunction
second_title: Aspose.Slides для Android через справочник Java API
description: Задает функцию аргумента.
type: docs
url: /ru/com.aspose.slides/imathfunction/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFunction extends IMathElement
```

Задаёт функцию аргумента.

--------------------

> ```
> Example:
>  
>  IMathFunction sinX = new MathematicalText("sin").function("x");
> ```
## Методы

| Метод | Описание |
| --- | --- |
| [getName()](#getName--) | Имя функции. Например, имена функций: sin и cos |
| [getBase()](#getBase--) | Аргумент функции |
### getName() {#getName--}
```
public abstract IMathElement getName()
```

Имя функции. Например, имена функций: sin и cos

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement funcName = func.getName();
> ```

**Возвращаемое значение:**
[IMathElement](../../com.aspose.slides/imathelement)
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Аргумент функции

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement base = func.getBase();
> ```

**Возвращаемое значение:**
[IMathElement](../../com.aspose.slides/imathelement)