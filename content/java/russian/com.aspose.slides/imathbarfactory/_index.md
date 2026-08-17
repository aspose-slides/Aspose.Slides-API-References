---
title: IMathBarFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a math bar
type: docs
url: /ru/com.aspose.slides/imathbarfactory/
---```
public interface IMathBarFactory
```

Позволяет создавать математическую черту

--------------------

Для совместимости с COM
## Методы

| Метод | Описание |
| --- | --- |
| [createMathBar(IMathElement element)](#createMathBar-com.aspose.slides.IMathElement-) | Create a math bar by applying to the element |
| [createMathBar(IMathElement element, int position)](#createMathBar-com.aspose.slides.IMathElement-int-) | Create a math bar by applying to the element |
### createMathBar(IMathElement element) {#createMathBar-com.aspose.slides.IMathElement-}
```
public abstract IMathBar createMathBar(IMathElement element)
```


Создаёт математическую черту, применяя к элементу

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | математический элемент, к которому применяется черта |

**Возврат:**
[IMathBar](../../com.aspose.slides/imathbar) - новый элемент математической черты
### createMathBar(IMathElement element, int position) {#createMathBar-com.aspose.slides.IMathElement-int-}
```
public abstract IMathBar createMathBar(IMathElement element, int position)
```


Создаёт математическую черту, применяя к элементу

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | математический элемент, к которому применяется черта |
| position | int | позиция черты |

**Возврат:**
[IMathBar](../../com.aspose.slides/imathbar) - новый элемент математической черты