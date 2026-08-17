---
title: IMathParagraphFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a math paragraph
type: docs
url: /de/com.aspose.slides/imathparagraphfactory/
---```
public interface IMathParagraphFactory
```

Ermöglicht das Erstellen eines mathematischen Absatzes

--------------------

Für COM-Kompatibilität
## Methoden

| Method | Description |
| --- | --- |
| [createMathParagraph()](#createMathParagraph--) | Erstelle einen leeren mathematischen Absatz |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | Erstellt einen mathematischen Absatz und platziert den angegebenen mathematischen Block darin |
### createMathParagraph() {#createMathParagraph--}
```
public abstract IMathParagraph createMathParagraph()
```


Erstelle einen leeren mathematischen Absatz

**Rückgabe:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - neuer mathematischer Absatz
### createMathParagraph(IMathBlock mathBlock) {#createMathParagraph-com.aspose.slides.IMathBlock-}
```
public abstract IMathParagraph createMathParagraph(IMathBlock mathBlock)
```


Erstellt einen mathematischen Absatz und platziert den angegebenen mathematischen Block darin

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | Mathematikblock, der im Absatz platziert werden soll |

**Rückgabe:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - neuer mathematischer Absatz