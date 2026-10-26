---
title: IMathFractionFactory
second_title: Aspose.Slides for Java API Reference
description: Lehetővé teszi egy matematikai tört létrehozását
type: docs
url: /hu/com.aspose.slides/imathfractionfactory/
---```
public interface IMathFractionFactory
```

Lehetővé teszi egy matematikai tört létrehozását

--------------------

COM kompatibilitásért
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Létrehozza a matematikai törtet |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Létrehozza a matematikai törtet |
### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```

Létrehozza a matematikai törtet

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Számláló |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Nevező |
| fractionType | int | Tört típusa |

**Visszatér:**
[IMathFraction](../../com.aspose.slides/imathfraction) - Új matematikai tört [IMathFraction](../../com.aspose.slides/imathfraction)
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```

Létrehozza a matematikai törtet

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Számláló |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Nevező |

**Visszatér:**
[IMathFraction](../../com.aspose.slides/imathfraction) - Új matematikai tört [IMathFraction](../../com.aspose.slides/imathfraction)