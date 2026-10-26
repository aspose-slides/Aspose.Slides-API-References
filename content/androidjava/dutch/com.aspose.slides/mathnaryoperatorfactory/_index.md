---
title: MathNaryOperatorFactory
second_title: Aspose.Slides voor Android via Java API Referentie
description: Stelt toe om IMathNaryOperator te maken
type: docs
url: /nl/com.aspose.slides/mathnaryoperatorfactory/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathNaryOperatorFactory](../../com.aspose.slides/imathnaryoperatorfactory)
```
public class MathNaryOperatorFactory implements IMathNaryOperatorFactory
```

Staat toe om IMathNaryOperator te creëren

--------------------

Voor COM-compatibiliteit
## Constructeurs

| Constructor | Beschrijving |
| --- | --- |
| [MathNaryOperatorFactory()](#MathNaryOperatorFactory--) |  |
## Methoden

| Method | Beschrijving |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creëert IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creëert IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | Creëert IMathNaryOperator |
### MathNaryOperatorFactory() {#MathNaryOperatorFactory--}
```
public MathNaryOperatorFactory()
```


### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```


Creëert IMathNaryOperator

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| operatorSymbol | char | Het operator teken |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Basisargument om operator toe te passen |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Ondergrens |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Bovengrens |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - nieuwe IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```


Creëert IMathNaryOperator

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| operatorSymbol | char | Het operator teken |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Basisargument om operator toe te passen |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Ondergrens |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - nieuwe IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```


Creëert IMathNaryOperator

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| operatorSymbol | char | Het operator teken |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Basisargument om operator toe te passen |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - nieuwe IMathNaryOperator