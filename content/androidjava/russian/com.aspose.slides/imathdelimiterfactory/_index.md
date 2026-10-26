---
title: IMathDelimiterFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math delimiter
type: docs
url: /ru/com.aspose.slides/imathdelimiterfactory/
---```
public interface IMathDelimiterFactory
```

Позволяет создавать математический разделитель

--------------------

Для совместимости с COM
## Методы

| Метод | Описание |
| --- | --- |
| [createMathDelimiter(IMathElement element)](#createMathDelimiter-com.aspose.slides.IMathElement-) | Создает математический разделитель, применяя к элементу |
| [createMathDelimiter(IMathElementCollection mathElements)](#createMathDelimiter-com.aspose.slides.IMathElementCollection-) | Создает математический разделитель, применяя к элементу |
### createMathDelimiter(IMathElement element) {#createMathDelimiter-com.aspose.slides.IMathElement-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElement element)
```


Создает математический разделитель, применяя к элементу

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | математический элемент для применения разделителя |

**Возвращаемое значение:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - новый математический разделитель
### createMathDelimiter(IMathElementCollection mathElements) {#createMathDelimiter-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElementCollection mathElements)
```


Создает математический разделитель, применяя к элементу

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | математические элементы для применения разделителя |

**Возвращаемое значение:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - новый математический разделитель