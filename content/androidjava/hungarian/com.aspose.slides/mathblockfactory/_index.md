---
title: MathBlockFactory
second_title: Aspose.Slides Androidhoz a Java API-referencia használatával
description: Lehetővé teszi egy matematikai blokk létrehozását
type: docs
url: /hu/com.aspose.slides/mathblockfactory/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IMathBlockFactory](../../com.aspose.slides/imathblockfactory)
```
public class MathBlockFactory implements IMathBlockFactory
```

Lehetővé teszi egy matematikai blokk létrehozását

--------------------

A COM kompatibilitáshoz
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [MathBlockFactory()](#MathBlockFactory--) |  |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | Matematikai blokk létrehozása |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | Matematikai blokk létrehozása és az elem elhelyezése benne |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | Matematikai blokk létrehozása és elemek elhelyezése benne |
### MathBlockFactory() {#MathBlockFactory--}
```
public MathBlockFactory()
```


### createMathBlock() {#createMathBlock--}
```
public final IMathBlock createMathBlock()
```


Matematikai blokk létrehozása

**Visszatér:**
[IMathBlock](../../com.aspose.slides/imathblock) - új matematikai blokk
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public final IMathBlock createMathBlock(IMathElement mathElement)
```


Matematikai blokk létrehozása és az elem elhelyezése benne

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Egy matematikai elem |

**Visszatér:**
[IMathBlock](../../com.aspose.slides/imathblock) - új matematikai blokk
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public final IMathBlock createMathBlock(IMathElementCollection mathElements)
```


Matematikai blokk létrehozása és elemek elhelyezése benne

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | matematikai elemek |

**Visszatér:**
[IMathBlock](../../com.aspose.slides/imathblock) - új matematikai blokk