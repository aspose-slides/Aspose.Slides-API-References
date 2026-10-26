---
title: IMathLimitFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create IMathLimit
type: docs
url: /es/com.aspose.slides/imathlimitfactory/
---```
public interface IMathLimitFactory
```

Permite crear IMathLimit

--------------------

Para compatibilidad con COM
## Métodos

| Método | Descripción |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | Crea IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Crea IMathLimit con límite en la parte inferior |
### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```

Crea IMathLimit

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Argumento base al que se aplica el límite |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Elemento de límite |
| upperLimit | boolean | Establece la posición del límite en la parte superior |

**Devuelve:**
[IMathLimit](../../com.aspose.slides/imathlimit) - nuevo límite matemático
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```

Crea IMathLimit con límite en la parte inferior

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Argumento base al que se aplica el límite |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Elemento de límite |

**Devuelve:**
[IMathLimit](../../com.aspose.slides/imathlimit) - nuevo límite matemático