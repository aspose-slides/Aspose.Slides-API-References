---
title: IMathFunction
second_title: Справка API Aspose.Slides для Java
description: Указывает функцию аргумента.
type: docs
url: /ru/com.aspose.slides/imathfunction/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFunction extends IMathElement
```

Указывает функцию аргумента.

--------------------

> ```
> Пример:
>  
>  IMathFunction sinX = new MathematicalText("sin").function("x");
> ```
## Методы

| Метод | Описание |
| --- | --- |
| [getName()](#getName--) | Имя функции. Например, имена функций — sin и cos |
| [getBase()](#getBase--) | Аргумент функции |
### getName() {#getName--}
```
public abstract IMathElement getName()
```


Имя функции. Например, имена функций — sin и cos

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement funcName = func.getName();
> ```

**Возвращает:**
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

**Возвращает:**
[IMathElement](../../com.aspose.slides/imathelement)