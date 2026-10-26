---
title: IMathRightSubSuperscriptElement
second_title: Справочник API Aspose.Slides для Java
description: Указывает объект Sub-Superscript, который состоит из базы и нижнего и верхнего индексов, размещенных справа от базы.
type: docs
url: /ru/com.aspose.slides/imathrightsubsuperscriptelement/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRightSubSuperscriptElement extends IMathElement
```

Определяет объект Sub-Superscript, который состоит из базы и нижнего и верхнего индексов, размещенных справа от базы.

--------------------

> ```
> Example:
>  
>  IMathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").setSubSuperscriptOnTheRight("i", "j");
> ```
## Методы

| Метод | Описание |
| --- | --- |
| [getBase()](#getBase--) | Аргумент базы |
| [getSubscript()](#getSubscript--) | Аргумент нижнего индекса |
| [getSuperscript()](#getSuperscript--) | Аргумент верхнего индекса |
| [getAlignScripts()](#getAlignScripts--) | Определяет выравнивание нижнего/верхнего индекса. |
| [setAlignScripts(boolean value)](#setAlignScripts-boolean-) | Определяет выравнивание нижнего/верхнего индекса. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Аргумент базы

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement baseElem = subsuperscript.getBase();
> ```

**Возвращает:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```


Аргумент нижнего индекса

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sub = subsuperscript.getSubscript();
> ```

**Возвращает:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```


Аргумент верхнего индекса

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sup = subsuperscript.getSuperscript();
> ```

**Возвращает:**
[IMathElement](../../com.aspose.slides/imathelement)
### getAlignScripts() {#getAlignScripts--}
```
public abstract boolean getAlignScripts()
```


Определяет выравнивание нижнего/верхнего индекса. Если значение истинно, нижний и верхний индексы выравниваются горизонтально относительно друг друга. Если значение ложно, они подгоняются под форму базы. Значение по умолчанию — false.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  subsuperscript.setAlignScripts(true);
> ```

**Возвращает:**
boolean
### setAlignScripts(boolean value) {#setAlignScripts-boolean-}
```
public abstract void setAlignScripts(boolean value)
```


Определяет выравнивание нижнего/верхнего индекса. Если значение истинно, нижний и верхний индексы выравниваются горизонтально относительно друг друга. Если значение ложно, они подгоняются под форму базы. Значение по умолчанию — false.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  subsuperscript.setAlignScripts(true);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |