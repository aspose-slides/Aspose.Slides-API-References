---
title: MathParagraphFactory
second_title: Aspose.Slides pro Android přes Java API Reference
description: Umožňuje vytvořit matematický odstavec
type: docs
url: /cs/com.aspose.slides/mathparagraphfactory/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IMathParagraphFactory](../../com.aspose.slides/imathparagraphfactory)
```
public class MathParagraphFactory implements IMathParagraphFactory
```

Umožňuje vytvořit matematický odstavec

--------------------

Pro kompatibilitu s COM
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [MathParagraphFactory()](#MathParagraphFactory--) |  |
## Metody

| Metoda | Popis |
| --- | --- |
| [createMathParagraph()](#createMathParagraph--) | Vytvořit prázdný matematický odstavec |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | Vytvoří matematický odstavec a umístí do něj zadaný matematický blok |
### MathParagraphFactory() {#MathParagraphFactory--}
```
public MathParagraphFactory()
```


### createMathParagraph() {#createMathParagraph--}
```
public final IMathParagraph createMathParagraph()
```

Vytvořit prázdný matematický odstavec

**Návratová hodnota:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - nový matematický odstavec
### createMathParagraph(IMathBlock mathBlock) {#createMathParagraph-com.aspose.slides.IMathBlock-}
```
public final IMathParagraph createMathParagraph(IMathBlock mathBlock)
```

Vytvoří matematický odstavec a umístí do něj zadaný matematický blok

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | matematický blok, který se má umístit do odstavce |

**Návratová hodnota:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - nový matematický odstavec