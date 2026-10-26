---
title: MathLimitFactory
second_title: Aspose.Slides para Android via Referência da API Java
description: Permite criar IMathLimit
type: docs
url: /pt/com.aspose.slides/mathlimitfactory/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IMathLimitFactory](../../com.aspose.slides/imathlimitfactory)
```
public class MathLimitFactory implements IMathLimitFactory
```

Permite criar IMathLimit

--------------------

Para compatibilidade COM
## Construtores

| Construtor | Descrição |
| --- | --- |
| [MathLimitFactory()](#MathLimitFactory--) |  |
## Métodos

| Método | Descrição |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | Cria IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Cria IMathLimit com limite na parte inferior |
### MathLimitFactory() {#MathLimitFactory--}
```
public MathLimitFactory()
```


### createMathLimit(IMMathElement baseArg, IMMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```


Cria IMathLimit

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Argumento base ao aplicar o limite |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Elemento de limite |
| upperLimit | boolean | Define a colocação do limite na parte superior |

**Retorna:**
[IMathLimit](../../com.aspose.slides/imathlimit) - novo limite matemático
### createMathLimit(IMMathElement baseArg, IMMathElement limit) {#createMathLimit-com.aspose.slides.IMMathElement-com.aspose.slides.IMMathElement-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```


Cria IMathLimit com limite na parte inferior

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Argumento base ao aplicar o limite |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Elemento de limite |

**Retorna:**
[IMathLimit](../../com.aspose.slides/imathlimit) - novo limite matemático