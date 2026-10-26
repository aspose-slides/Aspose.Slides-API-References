---
title: IMathFractionFactory
second_title: Referencia de la API de Aspose.Slides para Java
description: Permite crear una fracción matemática
type: docs
url: /es/com.aspose.slides/imathfractionfactory/
---```
public interface IMathFractionFactory
```

Permite crear una fracción matemática

--------------------

Para compatibilidad COM
## Métodos

| Método | Descripción |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Crea una fracción matemática |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Crea una fracción matemática |
### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```


Crea una fracción matemática

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Numerador |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Denominador |
| fractionType | int | Tipo de fracción |

**Devuelve:**
[IMathFraction](../../com.aspose.slides/imathfraction) - Nueva fracción matemática [IMathFraction](../../com.aspose.slides/imathfraction)
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```


Crea una fracción matemática

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Numerador |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Denominador |

**Devuelve:**
[IMathFraction](../../com.aspose.slides/imathfraction) - Nueva fracción matemática [IMathFraction](../../com.aspose.slides/imathfraction)