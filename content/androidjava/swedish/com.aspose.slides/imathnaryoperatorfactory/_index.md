---
title: IMathNaryOperatorFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Tillåter att skapa IMathNaryOperator
type: docs
url: /sv/com.aspose.slides/imathnaryoperatorfactory/
---```
public interface IMathNaryOperatorFactory
```

Tillåter att skapa IMathNaryOperator

--------------------

För COM-kompatibilitet
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Skapar IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Skapar IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | Skapar IMathNaryOperator |
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```


Skapar IMathNaryOperator

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| operatorSymbol | char | Operatörstecknet |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Basargument för att applicera operatör |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Nedre gräns |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Övre gräns |

**Returnerar:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - ny IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```


Skapar IMathNaryOperator

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| operatorSymbol | char | Operatörstecknet |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Basargument för att applicera operatör |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Nedre gräns |

**Returnerar:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - ny IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```


Skapar IMathNaryOperator

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| operatorSymbol | char | Operatörstecknet |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Basargument för att applicera operatör |

**Returnerar:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - ny IMathNaryOperator