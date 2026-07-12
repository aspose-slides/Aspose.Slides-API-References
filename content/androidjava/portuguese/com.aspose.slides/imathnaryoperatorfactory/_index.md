---
title: IMathNaryOperatorFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create IMathNaryOperator
type: docs
url: /pt/com.aspose.slides/imathnaryoperatorfactory/
---```
public interface IMathNaryOperatorFactory
```

Permite criar IMathNaryOperator

--------------------

Para compatibilidade COM
## Métodos

| Método | Descrição |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Cria IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Cria IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | Cria IMathNaryOperator |
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```

Cria IMathNaryOperator

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| operatorSymbol | char | O sinal do operador |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argumento base ao qual aplicar o operador |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Limite inferior |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Limite superior |

**Retorna:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - novo IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```

Cria IMathNaryOperator

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| operatorSymbol | char | O sinal do operador |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argumento base ao qual aplicar o operador |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Limite inferior |

**Retorna:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - novo IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```

Cria IMathNaryOperator

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| operatorSymbol | char | O sinal do operador |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argumento base ao qual aplicar o operador |

**Retorna:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - novo IMathNaryOperator