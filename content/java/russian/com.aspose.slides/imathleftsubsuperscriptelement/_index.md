---
title: IMathLeftSubSuperscriptElement
second_title: Справка API Aspose.Slides для Java
description: Определяет объект Sub-Superscript, который состоит из base и subscript и superscript, расположенных слева от base.
type: docs
url: /ru/com.aspose.slides/imathleftsubsuperscriptelement/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathLeftSubSuperscriptElement extends IMathElement
```

Определяет объект Sub-Superscript, который состоит из base и subscript и superscript, расположенных слева от base.

--------------------

> ```
> Example:
>  
>  IMathLeftSubSuperscriptElement leftSubsuperscript = new MathematicalText("N").setSubSuperscriptOnTheLeft("i", "j");
> ```
## Методы

| Метод | Описание |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getSubscript()](#getSubscript--) | Subscript |
| [getSuperscript()](#getSuperscript--) | Superscript |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Base argument

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathLeftSubSuperscriptElement leftSubSuperscript = new MathLeftSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement baseElem = leftSubSuperscript.getBase();
> ```

**Возвращает:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```


Subscript

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathLeftSubSuperscriptElement leftSubSuperscript = new MathLeftSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sub = leftSubSuperscript.getSubscript();
> ```

**Возвращает:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```


Superscript

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathLeftSubSuperscriptElement leftSubSuperscript = new MathLeftSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sup = leftSubSuperscript.getSuperscript();
> ```

**Возвращает:**
[IMathElement](../../com.aspose.slides/imathelement)