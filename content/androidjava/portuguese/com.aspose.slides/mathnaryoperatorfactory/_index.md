---
title: MathNaryOperatorFactory
second_title: Aspose.Slides para Android via Referência da API Java
description: Permite criar IMathNaryOperator
type: docs
url: /pt/com.aspose.slides/mathnaryoperatorfactory/
---
**Herança:**
java.lang.Object

**Todas as interfaces implementadas:**
[com.aspose.slides.IMathNaryOperatorFactory](../../com.aspose.slides/imathnaryoperatorfactory)
```
public class MathNaryOperatorFactory implements IMathNaryOperatorFactory
```

Permite criar IMathNaryOperator

--------------------

Para compatibilidade COM
## Construtores

| Construtor | Descrição |
| --- | --- |
| [MathNaryOperatorFactory()](#MathNaryOperatorFactory--) |  |
## Métodos

| Método | Descrição |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Cria IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Cria IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | Cria IMathNaryOperator |
### MathNaryOperatorFactory() {#MathNaryOperatorFactory--}
```
public MathNaryOperatorFactory()
```


### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```


Cria IMathNaryOperator

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| operatorSymbol | char | O símbolo do operador |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argumento base ao qual aplicar o operador |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Limite inferior |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Limite superior |

**Retorna:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - novo IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```


Cria IMathNaryOperator

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| operatorSymbol | char | O símbolo do operador |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argumento base ao qual aplicar o operador |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Limite inferior |

**Retorna:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - novo IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```


Cria IMathNaryOperator

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| operatorSymbol | char | O símbolo do operador |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argumento base ao qual aplicar o operador |

**Retorna:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - novo IMathNaryOperator