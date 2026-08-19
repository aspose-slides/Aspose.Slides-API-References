---
title: IMathNaryOperatorFactory
second_title: Aspose.Slides voor Java API-referentie
description: Maakt het mogelijk om IMathNaryOperator te maken
type: docs
url: /nl/com.aspose.slides/imathnaryoperatorfactory/
---```
public interface IMathNaryOperatorFactory
```

Maakt het mogelijk om IMathNaryOperator te maken

--------------------

Voor COM-compatibiliteit
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creëert IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creëert IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | Creëert IMathNaryOperator |
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```

Creëert IMathNaryOperator

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| operatorSymbol | char | Het operator-teken |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Basisargument om de operator toe te passen |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Ondergrens |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Bovengrens |

**Retourwaarde:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```

Creëert IMathNaryOperator

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| operatorSymbol | char | Het operator-teken |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Basisargument om de operator toe te passen |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Ondergrens |

**Retourwaarde:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```

Creëert IMathNaryOperator

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| operatorSymbol | char | Het operator-teken |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Basisargument om de operator toe te passen |

**Retourwaarde:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator