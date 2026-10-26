---
title: IMathNaryOperatorFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Staat toe een IMathNaryOperator te maken
type: docs
url: /nl/com.aspose.slides/imathnaryoperatorfactory/
---```
public interface IMathNaryOperatorFactory
```

Staat toe een IMathNaryOperator te maken

--------------------

Voor COM-compatibiliteit
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Maakt IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Maakt IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | Maakt IMathNaryOperator |
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```


Maakt IMathNaryOperator

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| operatorSymbol | char | Het operator-teken |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Basisargument om de operator op toe te passen |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Onderste limiet |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Bovenste limiet |

**Retour:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - nieuwe IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```


Maakt IMathNaryOperator

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| operatorSymbol | char | Het operator-teken |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Basisargument om de operator op toe te passen |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Onderste limiet |

**Retour:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - nieuwe IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```


Maakt IMathNaryOperator

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| operatorSymbol | char | Het operator-teken |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Basisargument om de operator op toe te passen |

**Retour:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - nieuwe IMathNaryOperator