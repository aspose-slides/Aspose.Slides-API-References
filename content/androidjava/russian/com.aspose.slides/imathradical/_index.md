---
title: IMathRadical
second_title: Ссылка на API Aspose.Slides для Android через Java
description: Задает радикальную функцию, состоящую из основания и необязательной степени.
type: docs
url: /ru/com.aspose.slides/imathradical/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRadical extends IMathElement
```

Задаёт радикальную функцию, состоящую из основания и необязательной степени. Пример радикального объекта — \\u221a\\ud835\\udc65.

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // кубический корень
```
## Методы

| Метод | Описание |
| --- | --- |
| [getBase()](#getBase--) | Аргумент Base |
| [getDegree()](#getDegree--) | Аргумент Degree |
| [getHideDegree()](#getHideDegree--) | Hide degree When истинно, степень не отображается, как в \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | Hide degree When истинно, степень не отображается, как в \\u221a\\ud835\\udc65 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Аргумент Base

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // кубический корень
>  IMathElement baseElem = radical.getBase();
>  ```


**Возвращает:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public abstract IMathElement getDegree()
```


Аргумент Degree

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // кубический корень
>  IMathElement degreeElem = radical.getDegree();
>  ```


**Возвращает:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public abstract boolean getHideDegree()
```


Hide degree When истинно, степень не отображается, как в \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // кубический корень
>  radical.setHideDegree(true);
>  ```


**Возвращает:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public abstract void setHideDegree(boolean value)
```


Hide degree When истинно, степень не отображается, как в \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // cube root
>  radical.setHideDegree(true);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |