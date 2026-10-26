---
title: IMathNaryOperatorFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create IMathNaryOperator
type: docs
url: /ru/com.aspose.slides/imathnaryoperatorfactory/
---```
public interface IMathNaryOperatorFactory
```

Позволяет создавать IMathNaryOperator

--------------------

Для совместимости с COM
## Методы

| Метод | Описание |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Создает IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Создает IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | Создает IMathNaryOperator |
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```

Создает IMathNaryOperator

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| operatorSymbol | char | Символ оператора |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Базовый аргумент для применения оператора |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Нижний предел |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Верхний предел |

**Возвращаемое значение:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - новый IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```

Создает IMathNaryOperator

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| operatorSymbol | char | Символ оператора |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Базовый аргумент для применения оператора |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Нижний предел |

**Возвращаемое значение:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - новый IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```

Создает IMathNaryOperator

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| operatorSymbol | char | Символ оператора |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Базовый аргумент для применения оператора |

**Возвращаемое значение:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - новый IMathNaryOperator