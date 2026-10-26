---
title: MathNaryOperatorFactory
second_title: Aspose.Slides voor Java API-referentie
description: Staat toe om IMathNaryOperator te maken
type: docs
url: /nl/com.aspose.slides/mathnaryoperatorfactory/
---
**Overerving:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathNaryOperatorFactory](../../com.aspose.slides/imathnaryoperatorfactory)
```
public class MathNaryOperatorFactory implements IMathNaryOperatorFactory
```

Staat toe om IMathNaryOperator te maken

--------------------

Voor COM-compatibiliteit
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [MathNaryOperatorFactory()](#MathNaryOperatorFactory--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Maakt IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Maakt IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | Maakt IMathNaryOperator |
### MathNaryOperatorFactory() {#MathNaryOperatorFactory--}
```
public MathNaryOperatorFactory()
```


### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```


Maakt IMathNaryOperator

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| operatorSymbol | char | Het operator-teken |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Basisargument om de operator toe te passen |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Ondergrens |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Bovengrens |

**Retour:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - nieuwe IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```


Maakt IMathNaryOperator

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| operatorSymbol | char | Het operator-teken |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Basisargument om de operator toe te passen |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Ondergrens |

**Retour:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - nieuwe IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```


Maakt IMathNaryOperator

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| operatorSymbol | char | Het operator-teken |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Basisargument om de operator toe te passen |

**Retour:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - nieuwe IMathNaryOperator