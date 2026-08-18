---
title: MathParagraphFactory
second_title: Aspose.Slides für Java API-Referenz
description: Ermöglicht das Erstellen eines mathematischen Absatzes
type: docs
url: /de/com.aspose.slides/mathparagraphfactory/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathParagraphFactory](../../com.aspose.slides/imathparagraphfactory)
```
public class MathParagraphFactory implements IMathParagraphFactory
```

Ermöglicht das Erstellen eines mathematischen Absatzes

--------------------

Für COM-Kompatibilität
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MathParagraphFactory()](#MathParagraphFactory--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createMathParagraph()](#createMathParagraph--) | Erstelle einen leeren mathematischen Absatz |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | Erstellt einen mathematischen Absatz und legt den angegebenen Matheblock darin ab |
### MathParagraphFactory() {#MathParagraphFactory--}
```
public MathParagraphFactory()
```


### createMathParagraph() {#createMathParagraph--}
```
public final IMathParagraph createMathParagraph()
```


Erstelle einen leeren mathematischen Absatz

**Rückgabewert:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - neuer mathematischer Absatz
### createMathParagraph(IMathBlock mathBlock) {#createMathParagraph-com.aspose.slides.IMathBlock-}
```
public final IMathParagraph createMathParagraph(IMathBlock mathBlock)
```


Erstellt einen mathematischen Absatz und legt den angegebenen Matheblock darin ab

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | Matheblock, der im Absatz platziert werden soll |

**Rückgabewert:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - neuer mathematischer Absatz