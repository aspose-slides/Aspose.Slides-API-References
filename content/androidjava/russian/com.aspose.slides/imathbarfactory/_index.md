---
title: IMathBarFactory
second_title: Aspose.Slides для Android через Java справочник API
description: Позволяет создать математическую черту
type: docs
url: /ru/com.aspose.slides/imathbarfactory/
---```
public interface IMathBarFactory
```

Позволяет создать математическую черту

--------------------

Для совместимости с COM
## Методы

| Метод | Описание |
| --- | --- |
| [createMathBar(IMathElement element)](#createMathBar-com.aspose.slides.IMathElement-) | Создать математическую черту, применяя к элементу |
| [createMathBar(IMathElement element, int position)](#createMathBar-com.aspose.slides.IMathElement-int-) | Создать математическую черту, применяя к элементу |
### createMathBar(IMathElement element) {#createMathBar-com.aspose.slides.IMathElement-}
```
public abstract IMathBar createMathBar(IMathElement element)
```

Создать математическую черту, применяя к элементу

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | математический элемент, к которому применяется черта |

**Возвращаемое значение:**
[IMathBar](../../com.aspose.slides/imathbar) - новый элемент математической черты
### createMathBar(IMathElement element, int position) {#createMathBar-com.aspose.slides.IMathElement-int-}
```
public abstract IMathBar createMathBar(IMathElement element, int position)
```

Создать математическую черту, применяя к элементу

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Математический элемент, к которому применяется черта |
| position | int | Позиция черты |

**Возвращаемое значение:**
[IMathBar](../../com.aspose.slides/imathbar) - новый элемент математической черты