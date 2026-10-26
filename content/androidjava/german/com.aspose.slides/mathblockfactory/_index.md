---
title: MathBlockFactory
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Ermöglicht das Erstellen eines Mathematikblocks
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

Ermöglicht das Erstellen eines Mathematikblocks

--------------------

Für COM-Kompatibilität
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MathBlockFactory()](#MathBlockFactory--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | Erstelle einen Mathematikblock |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | Erstelle einen Mathematikblock und platziere das Element darin |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | Erstelle einen Mathematikblock und platziere Elemente darin |
### MathBlockFactory() {#MathBlockFactory--}
```
public MathBlockFactory()
```


### createMathBlock() {#createMathBlock--}
```
public final IMathBlock createMathBlock()
```


Erstelle einen Mathematikblock

**Rückgabewert:**
[IMathBlock](../../com.aspose.slides/imathblock) - neuen Mathematikblock
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public final IMathBlock createMathBlock(IMathElement mathElement)
```


Erstelle einen Mathematikblock und platziere das Element darin

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Ein Mathelement |

**Rückgabewert:**
[IMathBlock](../../com.aspose.slides/imathblock) - neuen Mathematikblock
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public final IMathBlock createMathBlock(IMathElementCollection mathElements)
```


Erstelle einen Mathematikblock und platziere Elemente darin

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | Mathelemente |

**Rückgabewert:**
[IMathBlock](../../com.aspose.slides/imathblock) - neuen Mathematikblock