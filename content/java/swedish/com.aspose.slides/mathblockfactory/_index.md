---
title: MathBlockFactory
second_title: Aspose.Slides för Java API-referens
description: Tillåter att skapa ett math block
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

Tillåter att skapa ett math block

--------------------

För COM-kompatibilitet
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [MathBlockFactory()](#MathBlockFactory--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | Skapa ett math block |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | Skapa ett math block och placera elementet i det |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | Skapa ett math block och placera element i det |
### MathBlockFactory() {#MathBlockFactory--}
```
public MathBlockFactory()
```


### createMathBlock() {#createMathBlock--}
```
public final IMathBlock createMathBlock()
```

Skapa ett math block

**Returnerar:**
[IMathBlock](../../com.aspose.slides/imathblock) - ny math block
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public final IMathBlock createMathBlock(IMathElement mathElement)
```

Skapa ett math block och placera elementet i det

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Ett math-element |

**Returnerar:**
[IMathBlock](../../com.aspose.slides/imathblock) - ny math block
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public final IMathBlock createMathBlock(IMathElementCollection mathElements)
```

Skapa ett math block och placera element i det

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | math-element |

**Returnerar:**
[IMathBlock](../../com.aspose.slides/imathblock) - ny math block