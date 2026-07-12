---
title: IMathParagraphFactory
second_title: Aspose.Slides for Android via Java API Reference
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

| Methode | Beschreibung |
| --- | --- |
| [createMathParagraph()](#createMathParagraph--) | Erstelle leeren mathematischen Absatz |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | Erstellt einen mathematischen Absatz und legt den angegebenen Mathematikblock darin ab |
### createMathParagraph() {#createMathParagraph--}
```
public abstract IMathParagraph createMathParagraph()
```


Erstelle leeren mathematischen Absatz

**Rückgabewert:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - neuer mathematischer Absatz
### createMathParagraph(IMathBlock mathBlock) {#createMathParagraph-com.aspose.slides.IMathBlock-}
```
public abstract IMathParagraph createMathParagraph(IMathBlock mathBlock)
```


Erstellt einen mathematischen Absatz und legt den angegebenen Mathematikblock darin ab

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | Mathematikblock, der im Absatz platziert werden soll |

**Rückgabewert:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - neuer mathematischer Absatz