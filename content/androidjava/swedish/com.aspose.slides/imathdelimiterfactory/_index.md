---
title: IMathDelimiterFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Tillåter att skapa en matematikavgränsare
type: docs
url: /sv/com.aspose.slides/imathdelimiterfactory/
---```
public interface IMathDelimiterFactory
```

Tillåter att skapa en matematikavgränsare

--------------------

För COM-kompatibilitet
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createMathDelimiter(IMathElement element)](#createMathDelimiter-com.aspose.slides.IMathElement-) | Create a math delimiter by applying to the element |
| [createMathDelimiter(IMathElementCollection mathElements)](#createMathDelimiter-com.aspose.slides.IMathElementCollection-) | Create a math delimiter by applying to the element |
### createMathDelimiter(IMathElement element) {#createMathDelimiter-com.aspose.slides.IMathElement-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElement element)
```

Skapa en matematikavgränsare genom att tillämpa på elementet

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematik-element för att tillämpa avgränsare |

**Returnerar:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - ny matematikavgränsare
### createMathDelimiter(IMathElementCollection mathElements) {#createMathDelimiter-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElementCollection mathElements)
```

Skapa en matematikavgränsare genom att tillämpa på elementet

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | matematik-element för att tillämpa avgränsare |

**Returnerar:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - ny matematikavgränsare