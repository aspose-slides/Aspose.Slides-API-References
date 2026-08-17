---
title: IMathBlockFactory
second_title: Aspose.Slides für Java API-Referenz
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
| [createMathBlock()](#createMathBlock--) | Erstellt einen mathematischen Block |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | Erstellt einen mathematischen Block und platziert das Element darin |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | Erstellt einen mathematischen Block und platziert Elemente darin |
### createMathBlock() {#createMathBlock--}
```
public abstract IMathBlock createMathBlock()
```

Erstellt einen mathematischen Block

**Rückgabe:**
[IMathBlock](../../com.aspose.slides/imathblock) - neuer mathematischer Block
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock createMathBlock(IMathElement mathElement)
```

Erstellt einen mathematischen Block und platziert das Element darin

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Ein mathematisches Element |

**Rückgabe:**
[IMathBlock](../../com.aspose.slides/imathblock) - neuer mathematischer Block
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathBlock createMathBlock(IMathElementCollection mathElements)
```

Erstellt einen mathematischen Block und platziert Elemente darin

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | mathematische Elemente |

**Rückgabe:**
[IMathBlock](../../com.aspose.slides/imathblock) - neuer mathematischer Block