---
title: IMathFractionFactory
second_title: Aspose.Slides for Java API Reference
description: Consente di creare una frazione matematica
type: docs
url: /it/com.aspose.slides/imathfractionfactory/
---```
public interface IMathFractionFactory
```

Consente di creare una frazione matematica

--------------------

Per la compatibilità COM
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Crea una frazione matematica |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Crea una frazione matematica |
### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```


Crea una frazione matematica

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Numeratore |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Denominatore |
| fractionType | int | Tipo di frazione |

**Restituisce:**
[IMathFraction](../../com.aspose.slides/imathfraction) - Nuova frazione matematica [IMathFraction](../../com.aspose.slides/imathfraction)
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```


Crea una frazione matematica

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Numeratore |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Denominatore |

**Restituisce:**
[IMathFraction](../../com.aspose.slides/imathfraction) - Nuova frazione matematica [IMathFraction](../../com.aspose.slides/imathfraction)