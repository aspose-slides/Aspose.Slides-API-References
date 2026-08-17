---
title: IMathSubscriptElement
second_title: Справочник API Aspose.Slides для Java
description: Указывает объект субскрипта, который состоит из основания и уменьшенного субскрипта, расположенного снизу и справа.
type: docs
url: /ru/com.aspose.slides/imathsubscriptelement/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSubscriptElement extends IMathElement
```

Указывает объект субскрипта, который состоит из основания и уменьшенного субскрипта, расположенного снизу и справа.

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
> ```
## Методы

| Метод | Описание |
| --- | --- |
| [getBase()](#getBase--) | Базовый аргумент |
| [getSubscript()](#getSubscript--) | Субскрипт |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Базовый аргумент

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement baseElem = subscriptElement.getBase();
> ```

**Возвращаемое значение:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```

Субскрипт

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement sub = subscriptElement.getSubscript();
> ```

**Возвращаемое значение:**
[IMathElement](../../com.aspose.slides/imathelement)