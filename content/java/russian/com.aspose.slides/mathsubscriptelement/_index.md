---
title: MathSubscriptElement
second_title: Справочник API Aspose.Slides для Java
description: Определяет объект нижнего индекса, который состоит из базового элемента и уменьшенного подиндекса, размещённого ниже и справа.
type: docs
url: /ru/com.aspose.slides/mathsubscriptelement/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**Все реализованные интерфейсы:**
[com.aspose.slides.IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
```
public final class MathSubscriptElement extends BaseScript implements IMathSubscriptElement
```

Определяет объект нижнего индекса, который состоит из базового элемента и уменьшенного индекса, размещённого ниже и справа.

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
> ```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MathSubscriptElement(IMathElement baseArg, IMathElement subScript)](#MathSubscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Инициализирует новый экземпляр класса MathSubscriptElement. |
## Методы

| Метод | Описание |
| --- | --- |
| [getSubscript()](#getSubscript--) | Нижний индекс |
| [getChildren()](#getChildren--) | Получить дочерние элементы |
### MathSubscriptElement(IMathElement baseArg, IMathElement subScript) {#MathSubscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathSubscriptElement(IMathElement baseArg, IMathElement subScript)
```


Инициализирует новый экземпляр класса MathSubscriptElement.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| subScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```


Нижний индекс

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
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Получить дочерние элементы

**Возвращаемое значение:**
com.aspose.slides.IMathElement[]