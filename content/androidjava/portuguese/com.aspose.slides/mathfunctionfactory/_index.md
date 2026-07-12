---
title: MathFunctionFactory
second_title: Aspose.Slides para Android via Referência da API Java
description: Permite criar uma função matemática
type: docs
url: /pt/com.aspose.slides/mathfunctionfactory/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IMathFunctionFactory](../../com.aspose.slides/imathfunctionfactory)
```
public class MathFunctionFactory implements IMathFunctionFactory
```

Permite criar uma função matemática

--------------------

Para compatibilidade COM
## Construtores

| Construtor | Descrição |
| --- | --- |
| [MathFunctionFactory()](#MathFunctionFactory--) |  |
## Métodos

| Método | Descrição |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Cria função matemática |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Cria função matemática |
### MathFunctionFactory() {#MathFunctionFactory--}
```
public MathFunctionFactory()
```


### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```


Cria função matemática

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | Elemento usado como nome da função |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Elemento usado como argumento da função |

**Retorna:**
[IMathFunction](../../com.aspose.slides/imathfunction) - nova função matemática
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```


Cria função matemática

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| funcName | java.lang.String | Nome da função |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Elemento usado como argumento da função |

**Retorna:**
[IMathFunction](../../com.aspose.slides/imathfunction) - nova função matemática