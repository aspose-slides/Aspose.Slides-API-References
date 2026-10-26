---
title: IMathParagraphFactory
second_title: Aspose.Slides for Java API Reference
description: Tillåter att skapa ett matematiskt stycke
type: docs
url: /sv/com.aspose.slides/imathparagraphfactory/
---```
public interface IMathParagraphFactory
```

Tillåter att skapa ett matematiskt stycke

--------------------

För COM-kompatibilitet
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createMathParagraph()](#createMathParagraph--) | Skapa ett tomt matematiskt stycke |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | Skapar ett matematiskt stycke och placerar det angivna matematiska blocket i det |
### createMathParagraph() {#createMathParagraph--}
```
public abstract IMathParagraph createMathParagraph()
```


Skapa ett tomt matematiskt stycke

**Returnerar:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - nytt matematiskt stycke
### createMathParagraph(IMathBlock mathBlock) {#createMathParagraph-com.aspose.slides.IMathBlock-}
```
public abstract IMathParagraph createMathParagraph(IMathBlock mathBlock)
```


Skapar ett matematiskt stycke och placerar det angivna matematiska blocket i det

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | matematiskt block att placera i stycket |

**Returnerar:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - nytt matematiskt stycke