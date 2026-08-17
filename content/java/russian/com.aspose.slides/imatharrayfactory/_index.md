---
title: IMathArrayFactory
second_title: Aspose.Slides для Java справочник API
description: Позволяет создавать математический массив
type: docs
url: /ru/com.aspose.slides/imatharrayfactory/
---```
public interface IMathArrayFactory
```

Позволяет создавать математический массив

--------------------

Для совместимости с COM
## Методы

| Метод | Описание |
| --- | --- |
| [createMathArray(IMathElement element)](#createMathArray-com.aspose.slides.IMathElement-) | Creates a math array and places the specified element in it |
| [createMathArray(IMathElementCollection elements)](#createMathArray-com.aspose.slides.IMathElementCollection-) | Creates a math array and places specified elements in it |
### createMathArray(IMathElement element) {#createMathArray-com.aspose.slides.IMathElement-}
```
public abstract IMathArray createMathArray(IMathElement element)
```

Создает математический массив и помещает в него указанный элемент

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | математический элемент, который будет помещен в массив |

**Возвращаемое значение:**
[IMathArray](../../com.aspose.slides/imatharray) - новый математический массив
### createMathArray(IMathElementCollection elements) {#createMathArray-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathArray createMathArray(IMathElementCollection elements)
```

Создает математический массив и помещает в него указанные элементы

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| elements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | математические элементы, которые будут помещены в массив |

**Возвращаемое значение:**
[IMathArray](../../com.aspose.slides/imatharray) - новый математический массив