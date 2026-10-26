---
title: IMathFunctionFactory
second_title: Aspose.Slides for Java API Reference
description: Permite criar uma função matemática
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
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Cria uma função matemática |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Cria uma função matemática |
### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```


Cria uma função matemática

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | Elemento usado como nome da função |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Elemento usado como argumento da função |

**Retorna:**
[IMathFunction](../../com.aspose.slides/imathfunction) - nova função matemática
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```


Cria uma função matemática

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| funcName | java.lang.String | Nome da função |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Elemento usado como argumento da função |

**Retorna:**
[IMathFunction](../../com.aspose.slides/imathfunction) - nova função matemática