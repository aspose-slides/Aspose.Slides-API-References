---
title: IMathFunctionFactory
second_title: Aspose.Slides для Android через Java API Reference
description: Позволяет создавать математическую функцию
type: docs
url: /ru/com.aspose.slides/imathfunctionfactory/
---```
public interface IMathFunctionFactory
```

Позволяет создавать математическую функцию

--------------------

Для совместимости с COM
## Методы

| Метод | Описание |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates math function |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Creates math function |
### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```

Создает математическую функцию

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | Элемент, используемый в качестве имени функции |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Элемент, используемый в качестве аргумента функции |

**Возвращаемое значение:**
[IMathFunction](../../com.aspose.slides/imathfunction) - новая математическая функция
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```

Создает математическую функцию

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| funcName | java.lang.String | Имя функции |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Элемент, используемый в качестве аргумента функции |

**Возвращаемое значение:**
[IMathFunction](../../com.aspose.slides/imathfunction) - новая математическая функция