---
title: IMathFractionFactory
second_title: Aspose.Slides for Java API Reference
description: Permite criar uma fração matemática
type: docs
url: /pt/com.aspose.slides/imathfractionfactory/
---```
public interface IMathFractionFactory
```

Permite criar uma fração matemática

--------------------

Para compatibilidade COM
## Métodos

| Método | Descrição |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Cria uma fração matemática |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Cria uma fração matemática |
### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```

Cria uma fração matemática

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Numerador |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Denominador |
| fractionType | int | Tipo de fração |

**Retorno:**
[IMathFraction](../../com.aspose.slides/imathfraction) - Nova fração matemática [IMathFraction](../../com.aspose.slides/imathfraction)
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```

Cria uma fração matemática

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Numerador |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Denominador |

**Retorno:**
[IMathFraction](../../com.aspose.slides/imathfraction) - Nova fração matemática [IMathFraction](../../com.aspose.slides/imathfraction)