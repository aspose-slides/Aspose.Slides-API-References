---
title: IMathParagraphFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a math paragraph
type: docs
url: /hu/com.aspose.slides/imathparagraphfactory/
---```
public interface IMathParagraphFactory
```

Lehetővé teszi egy matematikai bekezdés létrehozását

--------------------

COM kompatibilitáshoz
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [createMathParagraph()](#createMathParagraph--) | Create empty math paragraph |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | Creates a math paragraph and places the specified math block in it |
### createMathParagraph() {#createMathParagraph--}
```
public abstract IMathParagraph createMathParagraph()
```


Üres matematikai bekezdés létrehozása

**Visszatér:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - new math paragraph
### createMathParagraph(IMathBlock mathBlock) {#createMathParagraph-com.aspose.slides.IMathBlock-}
```
public abstract IMathParagraph createMathParagraph(IMathBlock mathBlock)
```


Létrehozza a matematikai bekezdést és elhelyezi benne a megadott matematikai blokkot

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | a bekezdésbe elhelyezendő matematikai blokk |

**Visszatér:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - new math paragraph