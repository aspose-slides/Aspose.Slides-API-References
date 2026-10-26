---
title: MathNaryOperatorFactory
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Consente di creare IMathNaryOperator
type: docs
url: /it/com.aspose.slides/mathnaryoperatorfactory/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IMathNaryOperatorFactory](../../com.aspose.slides/imathnaryoperatorfactory)
```
public class MathNaryOperatorFactory implements IMathNaryOperatorFactory
```

Consente di creare IMathNaryOperator

--------------------

Per la compatibilità COM
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MathNaryOperatorFactory()](#MathNaryOperatorFactory--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Crea IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Crea IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | Crea IMathNaryOperator |
### MathNaryOperatorFactory() {#MathNaryOperatorFactory--}
```
public MathNaryOperatorFactory()
```


### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```


Crea IMathNaryOperator

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| operatorSymbol | char | Il segno dell'operatore |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argomento base su cui applicare l'operatore |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Limite inferiore |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Limite superiore |

**Restituisce:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```


Crea IMathNaryOperator

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| operatorSymbol | char | Il segno dell'operatore |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argomento base su cui applicare l'operatore |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Limite inferiore |

**Restituisce:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```


Crea IMathNaryOperator

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| operatorSymbol | char | Il segno dell'operatore |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argomento base su cui applicare l'operatore |

**Restituisce:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator