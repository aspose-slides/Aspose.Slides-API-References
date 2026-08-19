---
title: IMathDelimiterFactory
second_title: Aspose.Slides för Java API Reference
description: Tillåter att skapa en matematisk avgränsare
type: docs
url: /sv/com.aspose.slides/imathdelimiterfactory/
---```
public interface IMathDelimiterFactory
```

Tillåter att skapa en matematisk avgränsare

--------------------

För COM-kompatibilitet
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createMathDelimiter(IMathElement element)](#createMathDelimiter-com.aspose.slides.IMathElement-) | Skapa en matematisk avgränsare genom att tillämpa på elementet |
| [createMathDelimiter(IMathElementCollection mathElements)](#createMathDelimiter-com.aspose.slides.IMathElementCollection-) | Skapa en matematisk avgränsare genom att tillämpa på elementet |
### createMathDelimiter(IMathElement element) {#createMathDelimiter-com.aspose.slides.IMathElement-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElement element)
```

Skapa en matematisk avgränsare genom att tillämpa på elementet

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematikelement för att tillämpa avgränsare |

**Returnerar:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - ny matematisk avgränsare
### createMathDelimiter(IMathElementCollection mathElements) {#createMathDelimiter-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElementCollection mathElements)
```

Skapa en matematisk avgränsare genom att tillämpa på elementet

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | matematikelement för att tillämpa avgränsare |

**Returnerar:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - ny matematisk avgränsare