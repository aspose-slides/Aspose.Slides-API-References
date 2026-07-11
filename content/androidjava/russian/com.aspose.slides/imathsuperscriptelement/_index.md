---
title: IMathSuperscriptElement
second_title: Aspose.Slides для Android через справочник Java API
description: Указывает объект надстрочного знака, который состоит из основания и уменьшенного надстрочного знака, размещённого выше и справа
type: docs
url: /ru/com.aspose.slides/imathsuperscriptelement/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSuperscriptElement extends IMathElement
```

Указывает объект надстрочного знака, который состоит из основания и уменьшенного надстрочного знака, размещённого выше и справа

--------------------

> ```
> Example:
>  
>  IMathSuperscriptElement superscriptElement = new MathematicalText("N").setSuperscript("i");
```
## Методы

| Метод | Описание |
| --- | --- |
| [getBase()](#getBase--) | Базовый аргумент |
| [getSuperscript()](#getSuperscript--) | Надстрочный |
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
>  IMathElement superscript = new MathematicalText("i");
>  IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, subscript);
>  IMathElement baseElem = superscriptElement.getBase();
> ```

**Возвращаемое значение:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```

Надстрочный

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
>  IMathElement super = superscriptElement.getSuperscript();
> ```

**Возвращаемое значение:**
[IMathElement](../../com.aspose.slides/imathelement)