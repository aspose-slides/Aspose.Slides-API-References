---
title: IMathBlockFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Ermöglicht das Erstellen eines mathematischen Blocks
type: docs
url: /de/com.aspose.slides/imathblockfactory/
---```
public interface IMathBlockFactory
```

Ermöglicht das Erstellen eines mathematischen Blocks

--------------------

Für COM-Kompatibilität
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | Erstelle einen mathematischen Block |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | Erstelle einen mathematischen Block und platziere das Element darin |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | Erstelle einen mathematischen Block und platziere die Elemente darin |
### createMathBlock() {#createMathBlock--}
```
public abstract IMathBlock createMathBlock()
```


Erstelle einen mathematischen Block

**Rückgabewert:**
[IMathBlock](../../com.aspose.slides/imathblock) - neuer mathematischer Block
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock createMathBlock(IMathElement mathElement)
```


Erstelle einen mathematischen Block und platziere das Element darin

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Ein mathematisches Element |

**Rückgabewert:**
[IMathBlock](../../com.aspose.slides/imathblock) - neuer mathematischer Block
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathBlock createMathBlock(IMathElementCollection mathElements)
```


Erstelle einen mathematischen Block und platziere die Elemente darin

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | Mathematische Elemente |

**Rückgabewert:**
[IMathBlock](../../com.aspose.slides/imathblock) - neuer mathematischer Block