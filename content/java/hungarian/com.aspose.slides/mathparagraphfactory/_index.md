---
title: MathParagraphFactory
second_title: Aspose.Slides Java API Referenciája
description: Lehetővé teszi egy matematikai bekezdés létrehozását
type: docs
url: /hu/com.aspose.slides/mathparagraphfactory/
---
**Öröklés:**
java.lang.Object

**Az összes megvalósított interfész:**
[com.aspose.slides.IMathParagraphFactory](../../com.aspose.slides/imathparagraphfactory)
```
public class MathParagraphFactory implements IMathParagraphFactory
```

Lehetővé teszi egy matematikai bekezdés létrehozását

--------------------

COM kompatibilitáshoz
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [MathParagraphFactory()](#MathParagraphFactory--) |  |
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [createMathParagraph()](#createMathParagraph--) | Üres matematikai bekezdés létrehozása |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | Math bekezdést hoz létre és elhelyezi benne a megadott matematikai blokkot |
### MathParagraphFactory() {#MathParagraphFactory--}
```
public MathParagraphFactory()
```


### createMathParagraph() {#createMathParagraph--}
```
public final IMathParagraph createMathParagraph()
```


Üres matematikai bekezdés létrehozása

**Visszatér:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - új matematikai bekezdés
### createMathParagraph(IMathBlock mathBlock) {#createMathParagraph-com.aspose.slides.IMathBlock-}
```
public final IMathParagraph createMathParagraph(IMathBlock mathBlock)
```


Math bekezdést hoz létre és elhelyezi benne a megadott matematikai blokkot

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | a bekezdésbe helyezendő matematikai blokk |

**Visszatér:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - új matematikai bekezdés