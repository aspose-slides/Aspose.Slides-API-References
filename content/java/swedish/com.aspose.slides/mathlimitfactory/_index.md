---
title: MathLimitFactory
second_title: Aspose.Slides för Java API Referens
description: Tillåter att skapa IMathLimit
type: docs
url: /sv/com.aspose.slides/mathlimitfactory/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathLimitFactory](../../com.aspose.slides/imathlimitfactory)
```
public class MathLimitFactory implements IMathLimitFactory
```

Tillåter att skapa IMathLimit

--------------------

För COM-kompatibilitet
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [MathLimitFactory()](#MathLimitFactory--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | Skapar IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Skapar IMathLimit med limit längst ner |
### MathLimitFactory() {#MathLimitFactory--}
```
public MathLimitFactory()
```


### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```


Skapar IMathLimit

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Basargument för att tillämpa limit |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Gränselement |
| upperLimit | boolean | Ställer in placeringen av limit på toppen |

**Returnerar:**
[IMathLimit](../../com.aspose.slides/imathlimit) - ny math limit
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```


Skapar IMathLimit med limit längst ner

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Basargument för att tillämpa limit |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Gränselement |

**Returnerar:**
[IMathLimit](../../com.aspose.slides/imathlimit) - ny math limit