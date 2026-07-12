---
title: IMathFunctionFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math function
type: docs
url: /pt/com.aspose.slides/imathfunctionfactory/
---```
public interface IMathFunctionFactory
```

Permite criar uma função matemática

--------------------

Para compatibilidade COM
## Métodos

| Método | Descrição |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Cria função matemática |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Cria função matemática |
### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```

Cria função matemática

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | Elemento usado como nome da função |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Elemento usado como argumento da função |

**Retorno:**
[IMathFunction](../../com.aspose.slides/imathfunction) - nova função matemática
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```

Cria função matemática

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| funcName | java.lang.String | Nome da função |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Elemento usado como argumento da função |

**Retorno:**
[IMathFunction](../../com.aspose.slides/imathfunction) - nova função matemática