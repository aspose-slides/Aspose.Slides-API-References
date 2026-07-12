---
title: MathNaryOperatorFactory
second_title: Aspose.Slides para Android a través de la referencia de la API Java
description: Permite crear IMathNaryOperator
type: docs
url: /es/com.aspose.slides/mathnaryoperatorfactory/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IMathNaryOperatorFactory](../../com.aspose.slides/imathnaryoperatorfactory)
```
public class MathNaryOperatorFactory implements IMathNaryOperatorFactory
```

Permite crear IMathNaryOperator

--------------------

Para compatibilidad COM
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MathNaryOperatorFactory()](#MathNaryOperatorFactory--) |  |
## Métodos

| Método | Descripción |
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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| operatorSymbol | char | El signo del operador |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argumento base al que se aplica el operador |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Límite inferior |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Límite superior |

**Devuelve:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - nuevo IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```


Crea IMathNaryOperator

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| operatorSymbol | char | El signo del operador |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argumento base al que se aplica el operador |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Límite inferior |

**Devuelve:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - nuevo IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```


Crea IMathNaryOperator

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| operatorSymbol | char | El signo del operador |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argumento base al que se aplica el operador |

**Devuelve:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - nuevo IMathNaryOperator