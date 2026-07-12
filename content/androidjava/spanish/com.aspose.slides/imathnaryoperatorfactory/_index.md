---
title: IMathNaryOperatorFactory
second_title: Aspose.Slides para Android vía Referencia de API Java
description: Permite crear IMathNaryOperator
type: docs
url: /es/com.aspose.slides/imathnaryoperatorfactory/
---```
public interface IMathNaryOperatorFactory
```

Permite crear IMathNaryOperator

--------------------

Para compatibilidad COM
## Métodos

| Método | Descripción |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Crea IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Crea IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | Crea IMathNaryOperator |
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```

Crea IMathNaryOperator

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| operatorSymbol | char | El signo del operador |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argumento base al que aplicar el operador |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Límite inferior |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Límite superior |

**Devuelve:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - nuevo IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```

Crea IMathNaryOperator

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| operatorSymbol | char | El signo del operador |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argumento base al que aplicar el operador |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Límite inferior |

**Devuelve:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - nuevo IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```

Crea IMathNaryOperator

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| operatorSymbol | char | El signo del operador |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argumento base al que aplicar el operador |

**Devuelve:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - nuevo IMathNaryOperator