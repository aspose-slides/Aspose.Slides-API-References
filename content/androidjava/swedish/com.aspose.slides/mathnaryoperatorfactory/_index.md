---
title: MathNaryOperatorFactory
second_title: Aspose.Slides för Android via Java API-referens
description: Tillåter att skapa IMathNaryOperator
type: docs
url: /sv/com.aspose.slides/mathnaryoperatorfactory/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathNaryOperatorFactory](../../com.aspose.slides/imathnaryoperatorfactory)
```
public class MathNaryOperatorFactory implements IMathNaryOperatorFactory
```

Tillåter att skapa IMathNaryOperator

--------------------

För COM-kompatibilitet
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [MathNaryOperatorFactory()](#MathNaryOperatorFactory--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Skapar IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Skapar IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | Skapar IMathNaryOperator |
### MathNaryOperatorFactory() {#MathNaryOperatorFactory--}
```
public MathNaryOperatorFactory()
```


### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```


Skapar IMathNaryOperator

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| operatorSymbol | char | Operatorns tecken |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Basargument för att tillämpa operatorn |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Nedre gräns |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Övre gräns |

**Returnerar:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - ny IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```


Skapar IMathNaryOperator

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| operatorSymbol | char | Operatorns tecken |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Basargument för att tillämpa operatorn |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Nedre gräns |

**Returnerar:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - ny IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```


Skapar IMathNaryOperator

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| operatorSymbol | char | Operatorns tecken |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Basargument för att tillämpa operatorn |

**Returnerar:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - ny IMathNaryOperator