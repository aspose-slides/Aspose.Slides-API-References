---
title: IMathLimitFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Permite criar IMathLimit
type: docs
url: /pt/com.aspose.slides/imathlimitfactory/
---```
public interface IMathLimitFactory
```

Permite criar IMathLimit

--------------------

Para compatibilidade COM
## Métodos

| Método | Descrição |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | Cria IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Cria IMathLimit com limite na parte inferior |
### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```


Cria IMathLimit

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Argumento base ao aplicar o limite |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Elemento limite |
| upperLimit | boolean | Define a posição do limite na parte superior |

**Retorna:**
[IMathLimit](../../com.aspose.slides/imathlimit) - novo limite matemático
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```


Cria IMathLimit com limite na parte inferior

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Argumento base ao aplicar o limite |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Elemento limite |

**Retorna:**
[IMathLimit](../../com.aspose.slides/imathlimit) - novo limite matemático