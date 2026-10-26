---
title: MathFractionFactory
second_title: Aspose.Slides Android-hoz Java API referencia
description: Lehetővé teszi egy matematikai tört létrehozását
type: docs
url: /hu/com.aspose.slides/mathfractionfactory/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IMathFractionFactory](../../com.aspose.slides/imathfractionfactory)
```
public class MathFractionFactory implements IMathFractionFactory
```

Lehetővé teszi egy matematikai tört létrehozását

--------------------

COM kompatibilitáshoz
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [MathFractionFactory()](#MathFractionFactory--) |  |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Létrehoz egy matematikai tört |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Létrehoz egy matematikai tört |
### MathFractionFactory() {#MathFractionFactory--}
```
public MathFractionFactory()
```


### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```


Létrehoz egy matematikai tört

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Numerátor |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Denominátor |
| fractionType | int | Tört típusa |

**Visszatérési érték:**
[IMathFraction](../../com.aspose.slides/imathfraction) - új matematikai tört
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```


Létrehoz egy matematikai tört

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Numerátor |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Denominátor |

**Visszatérési érték:**
[IMathFraction](../../com.aspose.slides/imathfraction) - új matematikai tört