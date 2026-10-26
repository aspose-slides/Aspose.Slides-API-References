---
title: IMathRadical
second_title: Aspose.Slides для Java справочник API
description: Определяет радикальную функцию, состоящую из основания и необязательной степени.
type: docs
url: /ru/com.aspose.slides/imathradical/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRadical extends IMathElement
```

Определяет радикальную функцию, состоящую из основания и необязательной степени. Пример радикального объекта: \\u221a\\ud835\\udc65.

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // кубический корень
> ```
## Методы

| Метод | Описание |
| --- | --- |
| [getBase()](#getBase--) | Аргумент основания |
| [getDegree()](#getDegree--) | Аргумент степени |
| [getHideDegree()](#getHideDegree--) | Скрыть степень. Когда true, степень не отображается, как в \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | Скрыть степень. Когда true, степень не отображается, как в \\u221a\\ud835\\udc65 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Аргумент основания

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // кубический корень
>  IMathElement baseElem = radical.getBase();
> ```

**Возвращаемое значение:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public abstract IMathElement getDegree()
```


Аргумент степени

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // кубический корень
>  IMathElement degreeElem = radical.getDegree();
> ```

**Возвращаемое значение:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public abstract boolean getHideDegree()
```


Скрыть степень. Когда true, степень не отображается, как в \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // кубический корень
>  radical.setHideDegree(true);
> ```

**Возвращаемое значение:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public abstract void setHideDegree(boolean value)
```


Скрыть степень. Когда true, степень не отображается, как в \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // кубический корень
>  radical.setHideDegree(true);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |