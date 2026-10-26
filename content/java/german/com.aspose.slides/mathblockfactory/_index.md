---
title: MathBlockFactory
second_title: Aspose.Slides für Java API-Referenz
description: Ermöglicht das Erstellen eines Math-Blocks
type: docs
url: /de/com.aspose.slides/mathblockfactory/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathBlockFactory](../../com.aspose.slides/imathblockfactory)
```
public class MathBlockFactory implements IMathBlockFactory
```

Ermöglicht das Erstellen eines Math-Blocks

--------------------

Für COM-Kompatibilität
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MathBlockFactory()](#MathBlockFactory--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | Math-Block erstellen |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | Math-Block erstellen und das Element darin platzieren |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | Math-Block erstellen und Elemente darin platzieren |
### MathBlockFactory() {#MathBlockFactory--}
```
public MathBlockFactory()
```


### createMathBlock() {#createMathBlock--}
```
public final IMathBlock createMathBlock()
```


Math-Block erstellen

**Rückgabewert:**
[IMathBlock](../../com.aspose.slides/imathblock) – neuer Math-Block
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public final IMathBlock createMathBlock(IMathElement mathElement)
```


Math-Block erstellen und das Element darin platzieren

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Ein Math-Element |

**Rückgabewert:**
[IMathBlock](../../com.aspose.slides/imathblock) – neuer Math-Block
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public final IMathBlock createMathBlock(IMathElementCollection mathElements)
```


Math-Block erstellen und Elemente darin platzieren

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | Math-Elemente |

**Rückgabewert:**
[IMathBlock](../../com.aspose.slides/imathblock) – neuer Math-Block