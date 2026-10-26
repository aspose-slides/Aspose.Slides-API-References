---
title: IMathNaryOperatorFactory
second_title: Aspose.Slides dla Androida przez Java API Odniesienie
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
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | Creates IMathNaryOperator |
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```


Tworzy IMathNaryOperator

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| operatorSymbol | char | Znak operatora |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argument bazowy, do którego zastosować operator |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Dolna granica |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Górna granica |

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
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argument bazowy, do którego zastosować operator |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Dolna granica |

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
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argument bazowy, do którego zastosować operator |

**Zwraca:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - nowy IMathNaryOperator