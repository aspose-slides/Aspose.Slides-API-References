---
title: IMathNaryOperatorFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create IMathNaryOperator
type: docs
url: /it/com.aspose.slides/imathnaryoperatorfactory/
---```
public interface IMathNaryOperatorFactory
```

Consente di creare IMathNaryOperator

--------------------

Per compatibilità COM
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Crea IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Crea IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | Crea IMathNaryOperator |
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```


Crea IMathNaryOperator

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| operatorSymbol | char | Il segno dell'operatore |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argomento base a cui applicare l'operatore |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Limite inferiore |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Limite superiore |

**Restituisce:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - nuovo IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```


Crea IMathNaryOperator

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| operatorSymbol | char | Il segno dell'operatore |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argomento base a cui applicare l'operatore |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Limite inferiore |

**Restituisce:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - nuovo IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```


Crea IMathNaryOperator

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| operatorSymbol | char | Il segno dell'operatore |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argomento base a cui applicare l'operatore |

**Restituisce:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - nuovo IMathNaryOperator