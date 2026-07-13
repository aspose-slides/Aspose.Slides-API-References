---
title: IMathBlockFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Tillåter att skapa ett matematiskt block
type: docs
url: /sv/com.aspose.slides/imathblockfactory/
---```
public interface IMathBlockFactory
```

Tillåter att skapa ett matematiskt block

--------------------

För COM-kompatibilitet
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | Skapa ett matematiskt block |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | Skapa ett matematiskt block och placera elementet i det |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | Skapa ett matematiskt block och placera element i det |
### createMathBlock() {#createMathBlock--}
```
public abstract IMathBlock createMathBlock()
```

Skapa ett matematiskt block

**Returnerar:**
[IMathBlock](../../com.aspose.slides/imathblock) - nytt matematiskt block
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock createMathBlock(IMathElement mathElement)
```

Skapa ett matematiskt block och placera elementet i det

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Ett mattelement |

**Returnerar:**
[IMathBlock](../../com.aspose.slides/imathblock) - nytt matematiskt block
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathBlock createMathBlock(IMathElementCollection mathElements)
```

Skapa ett matematiskt block och placera element i det

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | mattelement |

**Returnerar:**
[IMathBlock](../../com.aspose.slides/imathblock) - nytt matematiskt block