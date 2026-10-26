---
title: MathLimitFactory
second_title: Referencia de API de Aspose.Slides para Android mediante Java
description: Permite crear IMathLimit
type: docs
url: /es/com.aspose.slides/mathlimitfactory/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IMathLimitFactory](../../com.aspose.slides/imathlimitfactory)
```
public class MathLimitFactory implements IMathLimitFactory
```

Permite crear IMathLimit

--------------------

Para compatibilidad COM
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MathLimitFactory()](#MathLimitFactory--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | Crea IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Crea IMathLimit con límite en la parte inferior |
### MathLimitFactory() {#MathLimitFactory--}
```
public MathLimitFactory()
```


### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```


Crea IMathLimit

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Argumento base al que aplicar el límite |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Elemento de límite |
| upperLimit | boolean | Establece la posición del límite en la parte superior |

**Devuelve:**
[IMathLimit](../../com.aspose.slides/imathlimit) - nuevo límite matemático
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```


Crea IMathLimit con límite en la parte inferior

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Argumento base al que aplicar el límite |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Elemento de límite |

**Devuelve:**
[IMathLimit](../../com.aspose.slides/imathlimit) - nuevo límite matemático