---
title: MathFunctionFactory
second_title: Справочник API Aspose.Slides для Java
description: Позволяет создавать математическую функцию
type: docs
url: /ru/com.aspose.slides/mathfunctionfactory/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IMathFunctionFactory](../../com.aspose.slides/imathfunctionfactory)
```
public class MathFunctionFactory implements IMathFunctionFactory
```

Позволяет создать математическую функцию

--------------------

Для совместимости с COM
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MathFunctionFactory()](#MathFunctionFactory--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Создаёт математическую функцию |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Создаёт математическую функцию |
### MathFunctionFactory() {#MathFunctionFactory--}
```
public MathFunctionFactory()
```


### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```


Создаёт математическую функцию

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | Элемент, используемый в качестве имени функции |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Элемент, используемый в качестве аргумента функции |

**Возвращаемое значение:**
[IMathFunction](../../com.aspose.slides/imathfunction) - новая математическая функция
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```


Создаёт математическую функцию

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| funcName | java.lang.String | Имя функции |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Элемент, используемый в качестве аргумента функции |

**Возвращаемое значение:**
[IMathFunction](../../com.aspose.slides/imathfunction) - новая математическая функция