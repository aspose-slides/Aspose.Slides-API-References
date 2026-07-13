---
title: MathLimitFactory
second_title: Aspose.Slides för Android via Java API-referens
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
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Skapar IMathLimit med gräns längst ner |
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
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Basargument för att tillämpa gränsen |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Gränselement |
| upperLimit | boolean | Anger placeringen av gränsen högst upp |

**Returnerar:**
[IMathLimit](../../com.aspose.slides/imathlimit) - ny matematisk gräns
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```


Skapar IMathLimit med gräns längst ner

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Basargument för att tillämpa gränsen |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Gränselement |

**Returnerar:**
[IMathLimit](../../com.aspose.slides/imathlimit) - ny matematisk gräns