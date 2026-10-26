---
title: MathParagraphFactory
second_title: Aspose.Slides för Android via Java API-referens
description: Tillåter att skapa ett matematiskt stycke
type: docs
url: /sv/com.aspose.slides/mathparagraphfactory/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathParagraphFactory](../../com.aspose.slides/imathparagraphfactory)
```
public class MathParagraphFactory implements IMathParagraphFactory
```

Tillåter att skapa ett matematiskt stycke

--------------------

För COM-kompatibilitet
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [MathParagraphFactory()](#MathParagraphFactory--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createMathParagraph()](#createMathParagraph--) | Skapa tomt matematiskt stycke |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | Skapar ett matematiskt stycke och placerar det angivna matematiska blocket i det |
### MathParagraphFactory() {#MathParagraphFactory--}
```
public MathParagraphFactory()
```


### createMathParagraph() {#createMathParagraph--}
```
public final IMathParagraph createMathParagraph()
```


Skapa tomt matematiskt stycke

**Returnerar:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - nytt matematiskt stycke
### createMathParagraph(IMathBlock mathBlock) {#createMathParagraph-com.aspose.slides.IMathBlock-}
```
public final IMathParagraph createMathParagraph(IMathBlock mathBlock)
```


Skapar ett matematiskt stycke och placerar det angivna matematiska blocket i det

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | matematiskt block att placera i stycket |

**Returnerar:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - nytt matematiskt stycke