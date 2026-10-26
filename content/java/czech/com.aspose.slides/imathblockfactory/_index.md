---
title: IMathBlockFactory
second_title: Aspose.Slides for Java API Reference
description: Umožňuje vytvořit matematický blok
type: docs
url: /cs/com.aspose.slides/imathblockfactory/
---```
public interface IMathBlockFactory
```

Umožňuje vytvořit matematický blok

--------------------

Pro kompatibilitu s COM
## Metody

| Metoda | Popis |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | Vytvořit matematický blok |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | Vytvořit matematický blok a umístit do něj prvek |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | Vytvořit matematický blok a umístit do něj prvky |
### createMathBlock() {#createMathBlock--}
```
public abstract IMathBlock createMathBlock()
```

Vytvořit matematický blok

**Vrací:**
[IMathBlock](../../com.aspose.slides/imathblock) - nový matematický blok
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock createMathBlock(IMathElement mathElement)
```

Vytvořit matematický blok a umístit do něj prvek

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Matematický prvek |

**Vrací:**
[IMathBlock](../../com.aspose.slides/imathblock) - nový matematický blok
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathBlock createMathBlock(IMathElementCollection mathElements)
```

Vytvořit matematický blok a umístit do něj prvky

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | matematické prvky |

**Vrací:**
[IMathBlock](../../com.aspose.slides/imathblock) - nový matematický blok