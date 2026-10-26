---
title: IMathParagraphFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Tillåter att skapa ett math paragraph
type: docs
url: /sv/com.aspose.slides/imathparagraphfactory/
---```
public interface IMathParagraphFactory
```

Tillåter att skapa ett math paragraph

--------------------

For COM comparibility
## Metoder

| Method | Description |
| --- | --- |
| [createMathParagraph()](#createMathParagraph--) | Skapa ett tomt math paragraph |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | Skapar ett math paragraph och placerar det angivna math block i det |
### createMathParagraph() {#createMathParagraph--}
```
public abstract IMathParagraph createMathParagraph()
```

Skapa ett tomt math paragraph

**Returnerar:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - new math paragraph
### createMathParagraph(IMathBlock mathBlock) {#createMathParagraph-com.aspose.slides.IMathBlock-}
```
public abstract IMathParagraph createMathParagraph(IMathBlock mathBlock)
```

Skapar ett math paragraph och placerar det angivna math block i det

**Parametrar:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | math block to place in the paragraph |

**Returnerar:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - new math paragraph