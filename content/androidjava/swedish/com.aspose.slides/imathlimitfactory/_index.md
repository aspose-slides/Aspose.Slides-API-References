---
title: IMathLimitFactory
second_title: Aspose.Slides för Android via Java API-referens
description: Tillåter att skapa IMathLimit
type: docs
url: /sv/com.aspose.slides/imathlimitfactory/
---```
public interface IMathLimitFactory
```

Tillåter att skapa IMathLimit

--------------------

För COM-kompatibilitet
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | Skapar IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Skapar IMathLimit med gräns längst ner |
### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```

Skapar IMathLimit

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Basargument för att tillämpa gränsen |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Gränselement |
| upperLimit | boolean | Anger placeringen av gränsen överst |

**Returnerar:**
[IMathLimit](../../com.aspose.slides/imathlimit) - ny matematisk gräns
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```

Skapar IMathLimit med gräns längst ner

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Basargument för att tillämpa gränsen |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Gränselement |

**Returnerar:**
[IMathLimit](../../com.aspose.slides/imathlimit) - ny matematisk gräns