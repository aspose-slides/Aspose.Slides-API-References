---
title: IMathFractionFactory
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: Lehetővé teszi matematikai tört létrehozását
type: docs
url: /hu/com.aspose.slides/imathfractionfactory/
---```
public interface IMathFractionFactory
```

Lehetővé teszi matematikai tört létrehozását

--------------------

A COM kompatibilitásért
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Matematikai törtet hoz létre |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Matematikai törtet hoz létre |
### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```


Matematikai törtet hoz létre

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Számláló |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Denominátor |
| fractionType | int | Tört típusa |

**Visszatérési érték:**
[IMathFraction](../../com.aspose.slides/imathfraction) - Új matematikai tört [IMathFraction](../../com.aspose.slides/imathfraction)
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```


Matematikai törtet hoz létre

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Számláló |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Denominátor |

**Visszatérési érték:**
[IMathFraction](../../com.aspose.slides/imathfraction) - Új matematikai tört [IMathFraction](../../com.aspose.slides/imathfraction)