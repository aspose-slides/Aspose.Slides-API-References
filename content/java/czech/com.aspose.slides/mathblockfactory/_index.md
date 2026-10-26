---
title: MathBlockFactory
second_title: Aspose.Slides pro Java API Reference
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
| [createMathBlock()](#createMathBlock--) | Create a math block |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | Create a math block and place the element in it |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | Create a math block and place elements in it |
### MathBlockFactory() {#MathBlockFactory--}
```
public MathBlockFactory()
```


### createMathBlock() {#createMathBlock--}
```
public final IMathBlock createMathBlock()
```


Vytvořit matematický blok

**Vrací:**
[IMathBlock](../../com.aspose.slides/imathblock) - nový matematický blok
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public final IMathBlock createMathBlock(IMathElement mathElement)
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
public final IMathBlock createMathBlock(IMathElementCollection mathElements)
```


Vytvořit matematický blok a umístit do něj prvky

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | matematické prvky |

**Vrací:**
[IMathBlock](../../com.aspose.slides/imathblock) - nový matematický blok