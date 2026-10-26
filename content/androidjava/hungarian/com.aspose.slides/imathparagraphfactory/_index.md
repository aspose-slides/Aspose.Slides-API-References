---
title: IMathParagraphFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Lehetővé teszi egy matematikai bekezdés létrehozását
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
| [createMathParagraph()](#createMathParagraph--) | Üres matematikai bekezdés létrehozása |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | Létrehoz egy matematikai bekezdést és elhelyezi benne a megadott matematikai blokkot |
### createMathParagraph() {#createMathParagraph--}
```
public abstract IMathParagraph createMathParagraph()
```

Üres matematikai bekezdés létrehozása

**Returns:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - új matematikai bekezdés
### createMathParagraph(IMathBlock mathBlock) {#createMathParagraph-com.aspose.slides.IMathBlock-}
```
public abstract IMathParagraph createMathParagraph(IMathBlock mathBlock)
```

Létrehoz egy matematikai bekezdést és elhelyezi benne a megadott matematikai blokkot

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | a bekezdésben elhelyezendő matematikai blokk |

**Visszatérési érték:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - új matematikiai bekezdés