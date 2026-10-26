---
title: MathNaryOperatorFactory
second_title: Aspose.Slides für Android über die Java API Referenz
description: Ermöglicht das Erstellen von IMathNaryOperator
type: docs
url: /de/com.aspose.slides/mathnaryoperatorfactory/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathNaryOperatorFactory](../../com.aspose.slides/imathnaryoperatorfactory)
```
public class MathNaryOperatorFactory implements IMathNaryOperatorFactory
```

Ermöglicht das Erstellen von IMathNaryOperator

--------------------

Für COM-Kompatibilität
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MathNaryOperatorFactory()](#MathNaryOperatorFactory--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Erstellt IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Erstellt IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | Erstellt IMathNaryOperator |
### MathNaryOperatorFactory() {#MathNaryOperatorFactory--}
```
public MathNaryOperatorFactory()
```


### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```


Erstellt IMathNaryOperator

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| operatorSymbol | char | Das Operatorsymbol |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Basisargument, auf das der Operator angewendet wird |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Untere Grenze |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Obere Grenze |

**Rückgabewert:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```


Erstellt IMathNaryOperator

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| operatorSymbol | char | Das Operatorsymbol |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Basisargument, auf das der Operator angewendet wird |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Untere Grenze |

**Rückgabewert:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```


Erstellt IMathNaryOperator

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| operatorSymbol | char | Das Operatorsymbol |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Basisargument, auf das der Operator angewendet wird |

**Rückgabewert:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator