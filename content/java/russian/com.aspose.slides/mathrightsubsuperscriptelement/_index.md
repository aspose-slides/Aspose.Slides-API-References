---
title: MathRightSubSuperscriptElement
second_title: Справочник API Aspose.Slides для Java
description: Указывает объект Sub-Superscript, который состоит из базы и нижнего и верхнего индексов, размещённых справа от базы.
type: docs
url: /ru/com.aspose.slides/mathrightsubsuperscriptelement/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**Все реализованные интерфейсы:**
[com.aspose.slides.IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
```
public final class MathRightSubSuperscriptElement extends BaseScript implements IMathRightSubSuperscriptElement
```

Указывает объект Sub-Superscript, который состоит из базы и нижнего и верхнего индексов, размещённых справа от базы.

--------------------

> ```
> Пример:
>  
>  MathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").SetSubSuperscriptOnTheRight("i", "j");
> ```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)](#MathRightSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Инициализирует новый экземпляр класса MathRightSubSuperscriptElement. |
## Методы

| Метод | Описание |
| --- | --- |
| [getSubscript()](#getSubscript--) | Аргумент нижнего индекса |
| [getSuperscript()](#getSuperscript--) | Аргумент верхнего индекса |
| [getAlignScripts()](#getAlignScripts--) | Указывает выравнивание нижнего/верхнего индекса. |
| [setAlignScripts(boolean value)](#setAlignScripts-boolean-) | Указывает выравнивание нижнего/верхнего индекса. |
| [getChildren()](#getChildren--) | Получить дочерние элементы |
### MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript) {#MathRightSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)
```


Инициализирует новый экземпляр класса MathRightSubSuperscriptElement.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| subScript | [IMathElement](../../com.aspose.slides/imathelement) |  |
| superScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```


Аргумент нижнего индекса

--------------------

> ```
> Пример:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sub = subsuperscript.getSubscript();
> ```

**Возвращаемое значение:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```


Аргумент верхнего индекса

--------------------

> ```
> Пример:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sup = subsuperscript.getSuperscript();
> ```

**Возвращаемое значение:**
[IMathElement](../../com.aspose.slides/imathelement)
### getAlignScripts() {#getAlignScripts--}
```
public final boolean getAlignScripts()
```


Указывает выравнивание нижнего/верхнего индекса. Когда значение true, нижний и верхний индексы выравниваются горизонтально друг относительно друга. Когда значение false, они подгоняются к форме базы. Значение по умолчанию — false.

--------------------

> ```
> Пример:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  subsuperscript.setAlignScripts(true);
> ```

**Возвращаемое значение:**
boolean
### setAlignScripts(boolean value) {#setAlignScripts-boolean-}
```
public final void setAlignScripts(boolean value)
```


Указывает выравнивание нижнего/верхнего индекса. Когда значение true, нижний и верхний индексы выравниваются горизонтально друг относительно друга. Когда значение false, они подгоняются к форме базы. Значение по умолчанию — false.

--------------------

> ```
> Пример:
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

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Получить дочерние элементы

**Возвращаемое значение:**
com.aspose.slides.IMathElement[]