---
title: MathBlockFactory
second_title: Aspose.Slides för Android via Java API-referens
description: Tillåter att skapa ett matematiskt block
type: docs
url: /sv/com.aspose.slides/mathblockfactory/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathBlockFactory](../../com.aspose.slides/imathblockfactory)
```
public class MathBlockFactory implements IMathBlockFactory
```

Tillåter att skapa ett matematiskt block

--------------------

För COM-kompatibilitet
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [MathBlockFactory()](#MathBlockFactory--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | Skapa ett matematiskt block |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | Skapa ett matematiskt block och placera elementet i det |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | Skapa ett matematiskt block och placera element i det |
### MathBlockFactory() {#MathBlockFactory--}
```
public MathBlockFactory()
```


### createMathBlock() {#createMathBlock--}
```
public final IMathBlock createMathBlock()
```


Skapa ett matematiskt block

**Returnerar:**
[IMathBlock](../../com.aspose.slides/imathblock) - nytt matematiskt block
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public final IMathBlock createMathBlock(IMathElement mathElement)
```


Skapa ett matematiskt block och placera elementet i det

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Ett matematiskt element |

**Returnerar:**
[IMathBlock](../../com.aspose.slides/imathblock) - nytt matematiskt block
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public final IMathBlock createMathBlock(IMathElementCollection mathElements)
```


Skapa ett matematiskt block och placera element i det

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | matematiska element |

**Returnerar:**
[IMathBlock](../../com.aspose.slides/imathblock) - nytt matematiskt block