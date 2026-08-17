---
title: MathNaryOperatorFactory
second_title: Справочник API Aspose.Slides для Java
description: Позволяет создавать IMathNaryOperator
type: docs
url: /ru/com.aspose.slides/mathnaryoperatorfactory/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IMathNaryOperatorFactory](../../com.aspose.slides/imathnaryoperatorfactory)
```
public class MathNaryOperatorFactory implements IMathNaryOperatorFactory
```

Позволяет создавать IMathNaryOperator

--------------------

Для совместимости с COM
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MathNaryOperatorFactory()](#MathNaryOperatorFactory--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Создаёт IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Создаёт IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | Создаёт IMathNaryOperator |
### MathNaryOperatorFactory() {#MathNaryOperatorFactory--}
```
public MathNaryOperatorFactory()
```

### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```

Создаёт IMathNaryOperator

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| operatorSymbol | char | Знак оператора |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Базовый аргумент для применения оператора |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Нижний предел |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Верхний предел |

**Возвращает:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - новый IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```

Создаёт IMathNaryOperator

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| operatorSymbol | char | Знак оператора |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Базовый аргумент для применения оператора |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Нижний предел |

**Возвращает:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - новый IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```

Создаёт IMathNaryOperator

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| operatorSymbol | char | Знак оператора |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Базовый аргумент для применения оператора |

**Возвращает:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - новый IMathNaryOperator