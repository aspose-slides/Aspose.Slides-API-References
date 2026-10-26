---
title: IMathNaryOperatorFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Ermöglicht das Erstellen von IMathNaryOperator
type: docs
url: /de/com.aspose.slides/imathnaryoperatorfactory/
---```
public interface IMathNaryOperatorFactory
```

Ermöglicht das Erstellen von IMathNaryOperator

--------------------

Für COM-Kompatibilität
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Erstellt IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Erstellt IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | Erstellt IMathNaryOperator |
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```


Erstellt IMathNaryOperator

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| operatorSymbol | char | Das Operatorsymbol |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Basisargument für den Operator |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Untere Grenze |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Obere Grenze |

**Rückgabewert:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```


Erstellt IMathNaryOperator

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| operatorSymbol | char | Das Operatorsymbol |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Basisargument für den Operator |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Untere Grenze |

**Rückgabewert:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```


Erstellt IMathNaryOperator

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| operatorSymbol | char | Das Operatorsymbol |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Basisargument für den Operator |

**Rückgabewert:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator