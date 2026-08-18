---
title: IMathNaryOperatorFactory
second_title: Aspose.Slides for Java API Reference
description: Umożliwia tworzenie IMathNaryOperator
type: docs
url: /pl/com.aspose.slides/imathnaryoperatorfactory/
---```
public interface IMathNaryOperatorFactory
```

Umożliwia tworzenie IMathNaryOperator

--------------------

Dla kompatybilności COM
## Metody

| Metoda | Opis |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Tworzy IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Tworzy IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | Tworzy IMathNaryOperator |
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```

Tworzy IMathNaryOperator

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| operatorSymbol | char | Znak operatora |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argument bazowy dla operatora |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Granica dolna |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Granica górna |

**Zwraca:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - nowy IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```

Tworzy IMathNaryOperator

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| operatorSymbol | char | Znak operatora |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argument bazowy dla operatora |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Granica dolna |

**Zwraca:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - nowy IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```

Tworzy IMathNaryOperator

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| operatorSymbol | char | Znak operatora |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argument bazowy dla operatora |

**Zwraca:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - nowy IMathNaryOperator