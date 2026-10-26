---
title: IMathBlockFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math block
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
| [createMathBlock()](#createMathBlock--) | Create a math block |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | Create a math block and place the element in it |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | Create a math block and place elements in it |
### createMathBlock() {#createMathBlock--}
```
public abstract IMathBlock createMathBlock()
```


Vytvoří matematický blok

**Vrací:**
[IMathBlock](../../com.aspose.slides/imathblock) - nový matematický blok
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock createMathBlock(IMathElement mathElement)
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
public abstract IMathBlock createMathBlock(IMathElementCollection mathElements)
```


Vytvoří matematický blok a umístí do něj prvky

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | matematické prvky |

**Vrací:**
[IMathBlock](../../com.aspose.slides/imathblock) - nový matematický blok