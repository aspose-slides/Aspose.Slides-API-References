---
title: MathBorderBoxFactory
second_title: Aspose.Slides för Android via Java API-referens
description: Tillåter att skapa en math border box
type: docs
url: /sv/com.aspose.slides/mathborderboxfactory/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathBorderBoxFactory](../../com.aspose.slides/imathborderboxfactory)
```
public class MathBorderBoxFactory implements IMathBorderBoxFactory
```

Tillåter att skapa en math border box

--------------------

För COM-kompatibilitet
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [MathBorderBoxFactory()](#MathBorderBoxFactory--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Skapa en math border box genom att tillämpa på elementet |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Skapa en math border box genom att tillämpa på elementet |
### MathBorderBoxFactory() {#MathBorderBoxFactory--}
```
public MathBorderBoxFactory()
```


### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element)
```


Skapa en math border box genom att tillämpa på elementet

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematiskt element för att applicera border box |

**Returnerar:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - nytt border box-element
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


Skapa en math border box genom att tillämpa på elementet

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematiskt element för att applicera border box |
| hideTop | boolean | Dölj överkant |
| hideBottom | boolean | Dölj nederkant |
| hideLeft | boolean | Dölj vänsterkant |
| hideRight | boolean | Dölj högerkant |
| strikethroughHorizontal | boolean | Border Box genomstrykning horisontell |
| strikethroughVertical | boolean | Border Box genomstrykning vertikal |
| strikethroughBottomLeftToTopRight | boolean | Border Box genomstrykning nedre vänster till övre högra |
| strikethroughTopLeftToBottomRight | boolean | Border Box genomstrykning övre vänster till nedre högra |

**Returnerar:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - nytt border box-element