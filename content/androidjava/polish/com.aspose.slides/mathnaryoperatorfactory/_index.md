---
title: MathNaryOperatorFactory
second_title: Aspose.Slides dla Androida poprzez odwołanie API Java
description: Umożliwia tworzenie IMathNaryOperator
type: docs
url: /pl/com.aspose.slides/mathnaryoperatorfactory/
---
**Dziedziczenie:**  
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**  
[com.aspose.slides.IMathNaryOperatorFactory](../../com.aspose.slides/imathnaryoperatorfactory)  
```
public class MathNaryOperatorFactory implements IMathNaryOperatorFactory
```

Umożliwia tworzenie IMathNaryOperator

--------------------

Dla kompatybilności COM
## Konstruktory

| Constructor | Description |
| --- | --- |
| [MathNaryOperatorFactory()](#MathNaryOperatorFactory--) |  |
## Metody

| Method | Description |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Tworzy IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Tworzy IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | Tworzy IMathNaryOperator |
### MathNaryOperatorFactory() {#MathNaryOperatorFactory--}
```
public MathNaryOperatorFactory()
```

### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```

Tworzy IMathNaryOperator

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| operatorSymbol | char | Znak operatora |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argument bazowy do zastosowania operatora |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Dolna granica |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Górna granica |

**Zwraca:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - nowy IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```

Tworzy IMathNaryOperator

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| operatorSymbol | char | Znak operatora |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argument bazowy do zastosowania operatora |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Dolna granica |

**Zwraca:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - nowy IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```

Tworzy IMathNaryOperator

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| operatorSymbol | char | Znak operatora |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argument bazowy do zastosowania operatora |

**Zwraca:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - nowy IMathNaryOperator