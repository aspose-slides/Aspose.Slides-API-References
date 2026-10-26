---
title: MathNaryOperatorFactory
second_title: Aspose.Slides pro Android přes referenci Java API
description: Umožňuje vytvořit IMathNaryOperator
type: docs
url: /cs/com.aspose.slides/mathnaryoperatorfactory/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IMathNaryOperatorFactory](../../com.aspose.slides/imathnaryoperatorfactory)
```
public class MathNaryOperatorFactory implements IMathNaryOperatorFactory
```

Umožňuje vytvořit IMathNaryOperator

--------------------

Pro kompatibilitu s COM
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [MathNaryOperatorFactory()](#MathNaryOperatorFactory--) |  |
## Metody

| Metoda | Popis |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Vytváří IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Vytváří IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | Vytváří IMathNaryOperator |
### MathNaryOperatorFactory() {#MathNaryOperatorFactory--}
```
public MathNaryOperatorFactory()
```

### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```

Vytváří IMathNaryOperator

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| operatorSymbol | char | Znak operátoru |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Základní argument pro použití operátoru |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Dolní mez |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Horní mez |

**Vrací:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - nový IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```

Vytváří IMathNaryOperator

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| operatorSymbol | char | Znak operátoru |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Základní argument pro použití operátoru |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Dolní mez |

**Vrací:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - nový IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```

Vytváří IMathNaryOperator

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| operatorSymbol | char | Znak operátoru |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Základní argument pro použití operátoru |

**Vrací:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - nový IMathNaryOperator