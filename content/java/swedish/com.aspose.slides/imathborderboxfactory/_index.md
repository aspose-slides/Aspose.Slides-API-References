---
title: IMathBorderBoxFactory
second_title: Aspose.Slides för Java API-referens
description: Tillåter att skapa en math border box
type: docs
url: /sv/com.aspose.slides/imathborderboxfactory/
---```
public interface IMathBorderBoxFactory
```

Tillåter att skapa en math border box

--------------------

För COM-kompatibilitet
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Skapa en math border box genom att tillämpa på elementet |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Skapa en math border box genom att tillämpa på elementet |
### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element)
```

Skapa en math border box genom att tillämpa på elementet

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | math-element att applicera border box på |

**Returnerar:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) – nytt border box-element
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Skapa en math border box genom att tillämpa på elementet

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | math-element att applicera border box på |
| hideTop | boolean | Dölj överkant |
| hideBottom | boolean | Dölj nederkant |
| hideLeft | boolean | Dölj vänster kant |
| hideRight | boolean | Dölj högerkant |
| strikethroughHorizontal | boolean | Border Box genomstrykning horisontell |
| strikethroughVertical | boolean | Border Box genomstrykning vertikal |
| strikethroughBottomLeftToTopRight | boolean | Border Box genomstrykning nedre vänster till övre höger |
| strikethroughTopLeftToBottomRight | boolean | Border Box genomstrykning övre vänster till nedre höger |

**Returnerar:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) – nytt border box-element