---
title: MathBlockFactory
second_title: Aspose.Slides pro Android přes Java API Reference
description: Umožňuje vytvořit matematický blok
type: docs
url: /cs/com.aspose.slides/mathblockfactory/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IMathBlockFactory](../../com.aspose.slides/imathblockfactory)
```
public class MathBlockFactory implements IMathBlockFactory
```

Umožňuje vytvořit matematický blok

--------------------

Pro kompatibilitu s COM
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [MathBlockFactory()](#MathBlockFactory--) |  |
## Metody

| Metoda | Popis |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | Vytvoří matematický blok |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | Vytvoří matematický blok a umístí do něj prvek |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | Vytvoří matematický blok a umístí do něj prvky |
### MathBlockFactory() {#MathBlockFactory--}
```
public MathBlockFactory()
```

### createMathBlock() {#createMathBlock--}
```
public final IMathBlock createMathBlock()
```

Vytvoří matematický blok

**Vrací:**
[IMathBlock](../../com.aspose.slides/imathblock) - nový matematický blok
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public final IMathBlock createMathBlock(IMathElement mathElement)
```

Vytvoří matematický blok a umístí do něj prvek

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Matematický prvek |

**Vrací:**
[IMathBlock](../../com.aspose.slides/imathblock) - nový matematický blok
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public final IMathBlock createMathBlock(IMathElementCollection mathElements)
```

Vytvoří matematický blok a umístí do něj prvky

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | matematické prvky |

**Vrací:**
[IMathBlock](../../com.aspose.slides/imathblock) - nový matematický blok